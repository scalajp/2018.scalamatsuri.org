---
name: Jakub Kozłowski
title: "Purely Functional HTTP clients for Free"
length: 40
audience: Intermediate
language: English
twitter: kubukoz
github: kubukoz
icon: https://pbs.twimg.com/profile_images/905069106692546561/CUboQNLQ.jpg
organization: Scala developer, Scalac
tags:
  - Functional Programming
  - Tools
  - Software Design and Architecture
suggestions:
  - people who want to write side-effect-free applications using HTTP APIs
---
Interfacing with external APIs is now part of almost every backend service. In essence, making HTTP calls involves side effects, and, as everyone who's had to test side effects knows, they are often a pain to test. Can we do something to integrate with these external services in a pure and functional way, and make them simpler to test? I say we can, with the Free monad.

I'll introduce an imperative HTTP client and gradually transform it into a purely functional one. Then I'll show how it can be used in Web API clients and how it all makes testing trivial.