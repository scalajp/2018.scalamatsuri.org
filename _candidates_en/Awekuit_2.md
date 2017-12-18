---
name: awekuit and Tomoyoshi Ogura
title: "A story of operating both Akka Streams Kafka and Kafka Streams"
length: 40
audience: Intermediate
language: Japanese
twitter: awekuit,tomoyoshi_ogura
github: awekuit,tarugo07
icon: https://pbs.twimg.com/profile_images/590112328756015104/kcSN89Am_400x400.jpg
organization: Chat Work, Inc
tags:
  - Big Data / Fast Data
  - Best Practices
suggestions:
  - People interested in both Akka and Kafka
  - People interested in Fast Data processing that's Reactive
---
In 2016, Chat Work rolled out a chat messaging microservice that adopted Akka HTTP and Akka Streams as the base, as well as Kafka Streams for Kafka event processing. In 2017, we are developing a Webhook microservice also using Akka HTTP and Akka Streams as the base, but we've opted for Akka Streams Kafka (formerly known as Reactive Kafka) to process Kafka events.

This is going to be a story about these two Kafka processing libraries, both operational in Chat Work. What are the differences? When should you use one over the other?
