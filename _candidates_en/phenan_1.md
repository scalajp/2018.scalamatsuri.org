---
name: phenan
title: "Auto generate DSL on Scala"
length: 40
audience: Intermediate
language: Japanese
twitter: phenan
github: phenan
icon: https://pbs.twimg.com/profile_images/663178783/enemy4_bigger.png
organization: The University of Tokyo
tags:
  - Tools
suggestions:
  - People who want to make a Scala library with a good API
  - People who are interested in application of Scala type systems
  - People who are interested in a phrase, "Type-checking time syntactic analysis"
---
You can create APIs looking like DSLs in Scala using method chains, implicits and other syntactic suger.
For example, ScalaTest provides an API which is similar to natural languages,
and ScalikeJDBC leverages method chains to provide SQL-like syntax for its API.
However, it is often very difficult to provide such sophisticated APIs.

Therefore, we developed a tool which automatically generates an API from your desired DSL grammars.
This tool allows you to easily generate APIs which look like natural languages, 
or APIs similar to other existing DSLs on Scala.
Internally this tool takes an advantage of Scala's type checking system and implements a LALR parser.
This session will introduce the tool itself, and discuss how to implement it.
