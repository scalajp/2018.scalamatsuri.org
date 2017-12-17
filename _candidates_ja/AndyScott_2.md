---
name: Andy Scott
title: "Deep dive into iota"
length: 40
audience: Advanced
language: English
twitter: andygscott
github: andyscott
icon: https://pbs.twimg.com/profile_images/941929774250827776/9hbZ-_8b_400x400.jpg
organization: Humanoid Extraordinaire @ Stripe
tags:
  - Functional Programming
  - Microservices
  - Others
suggestions:
  - This talk is intended for those who are already familiar with functional programming concepts such as coproducts and free monads.
---
Freestyle's iota is a high performance functional programming library
for very optimized coproducts. Its primary claim to fame is for
faster evaluation of Free Monads in Freestyle. However, iota has many
hidden features and can be used for much more than just Free.

Let's explore the current (and upcoming) features of iota while
looking at different functional programming patterns such as error
handling and generic typeclass derivation.

Additionally, we will briefly discuss how iota works behind-the-scenes
and take a peek at some of the underlying macros.
