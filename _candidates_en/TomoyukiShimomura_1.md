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
  - People who prefer type safety
  - People who have doubt about or feel dissatisfied with DI using Guice
---
Play Framework uses Google Guice as default even though it supports both JSR330 compatible runtime DI and compile time DI.
Although I often feel like I write Java code because of a bunch of annotations such as @Inject and @Singletation.  
In an earlier my project, my module ended up a huge one. It made me hard to test it.
In this session, I will talk about merit of compile time DI using MacWire, comparison with DI using Guice and its implementation.
Love typesafe!
