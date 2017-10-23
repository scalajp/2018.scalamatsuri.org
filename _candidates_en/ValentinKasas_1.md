---
name: Valentin Kasas
title: "Those 10000 case classes I never wrote"
length: 40
audience: Intermediate
language: English
twitter: ValentinKasas
github: vil1
icon: https://pbs.twimg.com/profile_images/832263608830668800/Sc3gPzek_400x400.jpg
organization: Freelance developer @ Kanaka
tags:
  - Big Data / Fast Data
  - Functional Programming
  - Software Design and Architecture
suggestions:
 - People who need to manipulate many different types of data safely
 - People interested in functional solutions to concrete problems
 - People curious about recursion schemes
---
When validating data with Spark, or read/writing it to Kafka topics, the go-to solution is to write a Scala case class or a Java Bean. But what if you had only 5 developers, 10000+ data structures and only a few months to ship your project? Let me show you how the power of hylomorphisms combined with expressive schemas allowed us to write the code that validates and transforms data from dozens of tables from hundred of data sources, and ship our project in time and on budget.
