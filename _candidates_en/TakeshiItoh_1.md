---
name: Takeshi Itoh @iTakeshi
title: "Metaprogramming in Scala: the Past and the Present"
length: 40
audience: Intermediate
language: Japanese
twitter: TaKeZo_I
github: iTakeshi
icon: https://avatars2.githubusercontent.com/u/1460175
organization: Robotic Biology Institute Inc., Nara Institute of Science And Technology
tags:
  - Tools
suggestions:
  - People who want to try metaprogramming using Scala
  - People who want to understand internal of libraries using metaprogramming
  - People want to contribute development of metaprogramming
---
In this talk, I will introduce the bleeding edge of metaprogramming utility
for Scala.

Since scala.reflect was shipped along with scala 2.10, metaprogramming
utility for scala evolved into scala.meta, and now it is moving toward
scala.macros. Furthermore, a project named scalagen has been started to
develop a novel static code generation tool.
In this unforeseeing situation, we, as Scala programmers, are required to
catch-up with the latest development status and to prepare for the
forthcoming revolution.
On the other hand, this big change offers us good opportunities to
contribute to the core functionality of Scala. Even though it seems
difficult to contribute the Scala compiler itself, there is a plenty of
room for us to contribute to the Scala metaprogramming ecosystem.

Based upon a review of the history of scala metaprogramming, I’d like to discuss about how to improve our programming experience with metaprogramming,
