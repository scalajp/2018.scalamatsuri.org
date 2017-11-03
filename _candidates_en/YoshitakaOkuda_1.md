---
name: Yoshitaka Okuda
title: "Lessons learned on Flow API implementation through development of ScalikeJDBC streams"
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
  - People who want to understand implementation of ScalikeJDBC streams
---
Did you know that Java 9 includes Flow API? Flow API is a standard specification of asynchronous stream processing, which is compatible with Reactive Streams specifications. It can unify connections between different components. Many libraries including Akka Streams and AWS Java SDK already support Flow API. However, Flow API only defines specification and does not include concrete implementation.
In this session, I will explain concrete implementation of Flow API (Reactive Streams) based on my experience through the development of a ScalikeJDBC Streams module. I will not cover the definition of Flow API.
