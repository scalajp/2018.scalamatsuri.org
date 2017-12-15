---
name: @j5ik2o
title: "Practical introduction to reactive DDD"
length: 40
audience: Intermediate
language: Japanese
twitter: j5ik2o
github: j5ik2o
icon: https://pbs.twimg.com/profile_images/634548604443607040/3XbAnLJx_400x400.jpg
organization: ChatWork
tags:
  - Software Design and Architecture
suggestions:
  - People who are interested in Akka and DDD
---
Reactive DDD is to architect reactive systems using domain driven design (DDD).
Chatwork has already fully integrated Akka into its systems, and has operated the systems for some time.
Based on inspirations from the experience in Chatwork, I will discuss and propose a new DDD architecture style.

The main topics are as follows:
 - The full picture of CQRS+Event Sourcing based system
 - Actors as aggregations, and persistent domain events
 - Combine a route of akka-http, use cases, and aggregation actor into a single Runnable Graph of Akka Streams
 - ReadModelUpdater and DAO implementation
 - BackOffSupervisor and CircuitBreaker for fault tolerance
