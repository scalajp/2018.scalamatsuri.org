---
name: Loic Knuchel
title: "Mutation testing, finally a good test quality measurement ?"
length: 40
audience: Beginner
language: English
twitter: loicknuchel
github: loicknuchel
icon: https://avatars0.githubusercontent.com/u/653009?s=460&v=4
organization: Software engineer at Criteo
tags:
  - Tools
suggestions:
  - People who want to improve testing their scala code
---
We all write tests (really?), but how to know if our tests are useful ?
- High number of tests ? Wrong, a lot of tests does not guarantee a working well application.
- High code coverage ? Wrong again, better but still not enough
What we really need is to see if our tests are really able to catch problems (in TDD the tests *must* fail before succeed to be sure they tests something).
So, let me present you: mutation testing !
This technique will alter your code, run the tests and expect them to fail. If not, you have missed something in your tests.
In this talk I will present more in detail the mutation testing technique, explain how to set it up for a scala project and show some results on a real project.
