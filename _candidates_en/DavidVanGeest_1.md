---
name: David van Geest
title: "Akka: A Best Friend (Forever!) for your Backend-for-Frontend"
length: 40
audience: Intermediate
language: English
twitter: DWvanGeest
github: DWvanGeest
icon: https://avatars3.githubusercontent.com/u/947530?s=460&v=4
organization: Senior Software Engineer, PagerDuty Inc.
tags:
  - Best Practices
  - Software Design and Architecture
  - Microservices
suggestions:
  - People interested in Akka Streams and HTTP
  - People interested in live UIs
  - People interested in microservice architectures
  - People who would like to build a Backend-for-Frontend
---
PagerDuty has been developing microservices which directly power our APIs. These microservices need generic edge concerns (like authentication) handled for them, and they need easy ways to provide data to end-users. That data is usually delivered in response to HTTP requests, but increasingly also delivered "live" via WebSockets.

Backends-for-Frontends (BFFs) is one pattern for addressing those needs. Attendees can expect to learn how PagerDuty implemented BFFs using Akka HTTP to proxy API requests and aggregate data, and Akka Streams to deliver live data from Kafka to our end-users.
