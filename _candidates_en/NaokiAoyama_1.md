---
name: Naoki Aoyama - @aoiroaoino
title: "Purely Functional Play Framework Application"
length: 40
audience: Advanced
language: Japanese
twitter: AoiroAoino
github: aoiroaoino
icon: https://pbs.twimg.com/profile_images/556312366862708736/jmQUaeoW_400x400.jpeg
organization: Septeni Original, Inc
tags:
  - Functional Programming
  - Software Design and Architecture
suggestions:
  - Those interested in practical functional programming
  - Those frustrated with runtime Dependency Injection
---
There is no doubt Play is a wonderful Web framework. It has many features, and embodies "Scalable" as it can be used from a small-scale throwaway app to a large-scale application. With a long history, and an official support, it is no overstatement to say that it's the de facto standard Web framework of Scala.

However, I do have some bones to pick. Among them is runtime Dependency Injection (DI) using Google Guice. It might well be an effective thing during large-scale applications development, but it's a cause of endless nuisance that makes your eyes doubt if you are still coding Scala. Heaven forbid should you chose to combine it with a Mock library during testing, you'll come across more NullPointerExceptions faster than the type system can save you.

In this session, I will propose an alternative way of implementing Play application using functional programming libraries such as Cats, doobie, Monix, and Monocle to build pure logics in a type-safe manner, such that they can be tested from any angle that you cut and dice.

Unfortunately, this will not a panacea that suits all tastes, but I hope to server as an energy drink for those who are tired of implementing boring apps.
