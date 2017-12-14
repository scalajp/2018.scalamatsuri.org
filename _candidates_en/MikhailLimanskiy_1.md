---
name: Mikhail Limanskiy
title: "Make your JavaBeans shapeless with BeanPurée"
length: 40
audience: Advanced
language: English
twitter: mike.limansky
github: limansky
icon: http://limansky.me/images/mikhail400x400.jpg
organization: 1-OFD
tags:
  - Functional Programming
  - Others
suggestions:
  - 1. People who use Scala as a primary language, but also have Java code in their projects. 
  - 2. People who would like to start using type level programming.
---
Sometimes you have to use some  Java code in your Scala project. It may force you to have a separate models in Scala and in Java. E.g. if you don’t want to use mutable classes in your Scala code. Or if you need to pass a data represented as a JavaBean to a Scala library which expects a case class.  BeanPurée is a library which brings generic programming to your JavaBeans. It can convert between Java and Scala models. But you can do many more than just to convert classes with it. I'd like to show you a number of type level programming examples with shapeless and BeanPurée.