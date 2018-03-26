---
name: Taisuke Oe
title: "How to get along with Implicit"
length: 40
audience: Beginner
language: Japanese
twitter: OE_uia
github: taisukeoe
icon: https://secure.gravatar.com/avatar/25fb3e7054e52e524817044853c2d4c3
organization: 
tags:
  - Best Practices
  - Intro to Scala
suggestions:
  - Scala newcomers feeling they haven't got used to implicit.
  - Scala programmers wanting to utilize implicit more.
slide_url: https://www.slideshare.net/TaisukeOe/how-to-get-along-with-implicits-91008535
youtube: https://youtu.be/ZKFIqwGp_B4
---
Scala has `implicit` in its keyword.
Library author can leverage implicit arguments to design concise, flexible and safer API which can be checked in compile time.

On the other hand,
newcomers might feel implicit arguments mystify how to use its API.
How can we check where required implicit values are defined?
Or, how should we define implicit values for our own data type?

In this talk, I will generalize pitfalls around implicit, and cover how to deal with them.
This talk won't require prior knowledge, but will introduce some advanced topics like induction of implicit values.
