---
name: Kai Sasaki
title: "Lessons learned while implementing my own distributed deep learning framework on Spark"
length: 40
audience: Intermediate
language: English
twitter: Lewuathe
github: Lewuathe
icon: https://secure.gravatar.com/avatar/e88b4d85c705c6d6e66f79a13cbd9c4c
organization: Software Engineer, Treasure Data
tags:
  - Big Data / Fast Data
  - Data Science / Machine Learning
suggestions:
  - People who are interested in distributed systems
  - People who have used Apache Spark before
---
TensorFlow, Caffe, Chainer are famous as general deep learning framework. But it is thought to be difficult to implement our own framework because of mathematics and peculiar notion such as calculation graph, autograd. In addition to this, making it scalable requires much harder work.
Apache Spark is a general distributed data processing engine written in Scala. In this session, I will talk what I learned while implementing my own distributed deep learning framework (dllib) on that platform.

- Model Parallelism and Data Parallelism
- Operator and Tensor abstraction
- Async Stochastic Gradient Descent
- Synchronization of model and Parameter Server
