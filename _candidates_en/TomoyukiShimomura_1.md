---
name: Tomoyuki Shimomura
title: "Introduction to compile time DI"
length: 10
audience: Beginner
language: Japanese
twitter: s10myk47
github: 
icon: https://pbs.twimg.com/profile_images/794027848122044416/84gSnh0o_400x400.jpg
organization: Septeni Original,Inc.
tags:
  - Best Practices
  - Software Design and Architecture
suggestions:
  - People who are typesafe
  - People who have doubts about or feel dissatisfied with DI using Guice
---
Play Framework uses Google Guice as its default even though it supports both JSR330 compatible runtime DI and compile time DI.
However, I often feel like I'm writing Java code due to the many annotations such as @Inject and @Singletation.  
An earlier project I worked on ended up becoming huge, which made it quite difficult to test.
In this session, I will discuss the merits of compile time DI using MacWire, compare it with DI using Guice and describe its implementation.
I love typesafe!
