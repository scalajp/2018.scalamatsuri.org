---
name: Jasper van Zandbeek
title: "Purely functional microservices with http4s and doobie"
length: 40
audience: Beginner
language: English
twitter: jaspervanzand
github: jaspervz
icon: https://avatars2.githubusercontent.com/u/2083625
organization: Freelance Scala Developer
tags:
  - Microservices
suggestions:
  - People who have no or some experience with microservices and want to write them in a more functional way
---
As functional programmers we want to compose pure functions, allowing us to reason easier without needing to worry about possible side effects. 
But how to compose pure functions into real world microservices, which are frequently created using the standard Scala futures and are therefore impure in nature? Is this an area in which we unfortunately need to lose part of the pureness? Or is there an alternative?

Fortunately, using http4s (http://http4s.org/) and doobie (http://tpolecat.github.io/doobie/) together it is possible to create a pure functional microservice in which side effects are pushed to the border of the application. This talk aimed at beginners shows how to do this.

With http4s you create a web application is a functional way. The latest version uses the cats IO monad for this. This talk will explain the difference between a standard Scala future and the cats IO monad and why using a future leads to a non-pure function. It continues showing how to build a simple microservice using http4s.

Next, it will give a short introduction to doobie, a pure functional way for database access, which also uses the cats IO monad.
Because both http4s and doobie use the IO monad, combining them is natural, as this talk will show. It also shows how to do the initialization of the database connection pool in a functional way.

fs2 (https://github.com/functional-streams-for-scala/fs2), functional streams for Scala, are used both in http4s and doobie. After a brief introduction of fs2, this talk will show how to stream the database results to the http layer in a pure functional way, resulting in smaller memory footprint than when reading all results from the database into memory before outputting them to the client.

The talk ends with how to perform unit and integration tests for a microservice built in http4s and doobie.
