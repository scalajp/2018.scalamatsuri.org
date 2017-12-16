---
name: Yusuke Yasuda (@TanUkkii007)
title: "The internals of ChatWork’s Snowflake-like distributed ID generator powered by Akka and ZooKeeper"
length: 40
audience: Intermediate
language: Japanese
twitter: TanUkkii007
github: TanUkkii007
icon: https://avatars0.githubusercontent.com/u/2936722?s=460&v=4
organization: ChatWork
tags:
  - Best Practices
  - Software Design and Architecture
  - Microservices
suggestions:
  - Those interested in the affinity of actor programming in the context of distributed consensus application.
  - Those interested in how distributed IDs are used in the largest business chat service in Japan.
  - Those who want to build distributed systems using Akka.
---
In the spring of 2017, ChatWork migrated its IDs to 64 bits. The new ID maintains compatibility with the old relational database (RDB) ID, but it is now able to be generated in a distributed manner like Twitter Snowflake. The distributed ID generator is capable of issuing 4,0000 IDs per second per machine, and it's 10ms faster than the old generator in terms of latency.

The distributed ID generator is implemented using Akka and ZooKeeper. A ZooKeeper application must be:

1. Passive
2. State machine
3. Robust against errors such as loss of connection, and
4. Able to discard state upon the expiration of the session.

These can be implemented naturally using actors. In additon, the location transparency and the multi-jvm testkit from Akka makes testing a breeze.

In this session, I will explain the internals of the new ID generator from the point of view of combining actors with ZooKeeper.
