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
As functional programmers we want to compose pure functions, allowing us
to reason easier without needing to worry about side effects.

But how to compose pure functions into microservices, which are
frequently created using the Scala futures and are therefore impure in
nature? Is this an area in which we need to lose part of the pureness?
Or is there an alternative?

Using http4s and doobie together it is possible to create a pure
functional microservice in which side effects are pushed to the border
of the application. This talk aimed at beginners shows how to do this.
