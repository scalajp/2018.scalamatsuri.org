---
name: Kotaro Tanahashi, Yoshihito Hotta
title: "Development of Scala based DSL for Quantum Annealing"
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
---
We have involved in a joint research on Quantum Annealing (QA) with Waseda University and D-Wave Systems Inc. based in Canada.
To solve an optimization problem in a QA machine, you need describe the problem in a special format called QUBO and map it based on hardware structure.
QA machine has been becoming larger year by year, so this mapping has been more difficult to implement from the scratch.
So, we have tried the following by implementing Scala based DSL for QA.

* constructive and abstract representation of optimization problems based on combination of functions
* natural adaption of optimized circuit layout information in the representation

As the rise of hardware description language has made large-scale integrated circuit easier, I hope our Scala based DSL will improve productivity of software development for QA.
