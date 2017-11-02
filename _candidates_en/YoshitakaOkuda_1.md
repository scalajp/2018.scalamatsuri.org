---
name: Yoshitaka Okuda
title: "Lesson learned on Flow API implementation through development of ScalikeJDBC streams"
length: 40
audience: Intermediate
language: Japanese
twitter: yoskhdia
github: yoskhdia
icon: https://pbs.twimg.com/profile_images/814301502516826112/tkeIfq1H_400x400.jpg
organization: Supership Inc.
tags:
  - Best Practices
  - Software Design and Architecture
  - Others
suggestions:
  - People who want to understand implementation of Flow API(Reactive Streams) and how to use it
  - People who want to use Flow API
  - People who want to know implementation of ScalikeJDBC streams
---
Do you know Java 9 includes Flow API? Flow API is a standard specification of asynchronous stream processing, which is compatible with Reactive Streams specification. It can unify connections between different components. Many libraries including Akka Streams and AWS Java SDK has already started support of Flow API. But Flow API just defines specification and does not include concrete implementation.
In this session, I will explain concrete implementation of Flow API (Reactive Streams) based on my experience through development of ScalikeJDBC Streams module. I will not cover definition of Flow API.
