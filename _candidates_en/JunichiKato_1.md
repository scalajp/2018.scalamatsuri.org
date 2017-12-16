---
name: Junichi Kato
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
Reactive DDD is used to architect reactive systems using domain driven design (DDD).
ChatWork has already fully integrated Akka into its systems and has operated these systems for some time.
Based on inspiration from my experience with ChatWork, I will discuss and propose a new DDD architecture style.

The main topics of this talk are as follows:
 - The full picture of CQRS+Event Sourcing based systems
 - Actors as aggregations and persistent domain events
 - Combination of a route of akka-http, use cases, and aggregation actors into a single Runnable Graph of Akka Streams
 - ReadModelUpdater and DAO implementation
 - BackOffSupervisor and CircuitBreaker for fault tolerance
