---
name: Kim-Ee Yeoh
title: "Beautiful Logging with Category Theory: Why The Writer Monad Is Unfit for Logging and Which Monad To Replace It With"
length: 40
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
  - Anyone who wants to write Scala without risking public shaming for misusing abstractions.
---
Every category theory guru you've read explains the Writer monad using logging as an example. But logging is a bad example because—despite the name—the definition of the Writer monad allows reads—and worse, modifications—of the whole log. This can't be right for two reasons. It's too costly. And logs are typically only written to, never read from and definitely not modified.

So what is the category-theoretic correct way to do logging?

This talk delivers three benefits. It gives you the answer. You'll see a free monad in action. And you'll understand the theory better than before.

