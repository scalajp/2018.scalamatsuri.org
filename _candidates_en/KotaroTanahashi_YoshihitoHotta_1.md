---
name: Kotaro Tanahashi, Yoshihito Hotta
title: "Development of DSL for Quantum Annealing with Recursive Scheme"
length: 10
audience: Intermediate
language: Japanese
twitter:
github:
icon: https://pbs.twimg.com/profile_images/1154146189/1029656369_dsc08417_400x400.jpg
organization: Recruit Communications Co., Ltd.
tags:
  - Functional Programming
  - Tools
  - Data Science / Machine Learning
suggestions:
  - People who want to solve optimization problems using Scala
  - People who are interested in quantum annealing
slide_url:
youtube: https://youtu.be/wYnqtwvfzos
---
We have been involved in joint research on Quantum Annealing (QA) with Waseda University and D-Wave Systems Inc. (based in Canada).
To solve an optimization problem in a QA machine, you need to describe the problem in a special format called QUBO and map it based on hardware structure.
QA machines have become larger year by year, so this mapping has been increasingly more difficult to implement from scratch.
In response, we have tried to achieve the following by implementing a Scala-based DSL for QA.

* constructive and abstract representation of optimization problems based on a combination of functions
* natural adaption of optimized circuit layout information in the representation

Just as the rise of hardware description language has made large-scale integrated circuits easier, I hope that our Scala-based DSL will improve the productivity of software development for QA.
