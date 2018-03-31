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
slide_url: https://www.slideshare.net/AoiroAoino/purelyfunctionalplayframeworkapplication
youtube: https://youtu.be/LtnT8SPKAqU
---
There is no doubt that Play is a wonderful Web framework. It has many features and embodies the term "scalable", as it can be used in a multitude of scenarios, from a small-scale throwaway app to a large-scale application. With its long history, and an official support, it is no overstatement to say that it's the de facto standard Web framework of Scala.

However, I do have some bones to pick with Play. Among them is runtime Dependency Injection (DI) using Google Guice. It may well be an effective tool during large-scale applications development, but it's also a cause of endless annoyance that sometimes makes you doubt if you are indeed still coding in Scala. Heaven forbid should you also choose to combine it with a Mock library during testing; you'll come across NullPointerExceptions faster than the type system can save you.

In this session, I will propose an alternative method of implementing the Play application using functional programming libraries such as Cats, doobie, Monix, and Monocle. I will use these to build pure logics in a type-safe manner, such that they can be analyzed from any angles that you choose to slice and dice.

Unfortunately, this method will not be a panacea that suits all tastes, but I hope it serves as an energy drink for those who are tired of implementing boring apps.
