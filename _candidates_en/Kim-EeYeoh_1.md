---
name: Kim-Ee Yeoh
title: "Beautiful Random Numbers With Category Theory: Why The State Monad Isn't Ideal and Which Monad Is Superior"
length: 10
audience: Intermediate
language: English
twitter: ky3atamo
github: 
icon: http://ruby.id/images/conf/2017/abdullah-pic.jpg
organization: 
tags:
  - Functional Programming
  - Best Practices
  - Microservices
suggestions:
  - Scala developers who want snugger fitting abstractions that don't leak as much allowing bugs to get in.
---
Random Number Generation is typically modeled using the State monad. But the State monad is overkill because the client app has write access to the seed. So the app may replay random numbers and it may also break the generator by making it return 9, 9, 9 all the time.

Ideally the client only reads random numbers. Seed-setting occurs at a different level altogether.

So what is the category-theoretic correct way to model the RNG interface?

This talk delivers three benefits. It gives you the answer. You'll see a free monad in action. And you'll leverage duality for better recall of the theory.

