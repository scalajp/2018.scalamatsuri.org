---
name: 小椋 友芳
title: "Scalaでスケーラブルかつハイアベイラビリティなサービスを開発するためのヒント"
title: "How to develop scalable and high availability services using Scala"
length: 40
audience: Beginner
language: Japanese
twitter: tomoyoshi_ogura
github: tarugo07
icon: https://pbs.twimg.com/profile_images/941557571831324673/_prrpo1D_400x400.jpg
organization: ChatWork
tags:
  - Software Design and Architecture
  - Microservices
  - Others
suggestions:
  - People who are interested in service development using Scala
---
Various problems occur in development of services that process continuous and enormous data. It is quite difficult problem to improve their throughput while keeping highly stabile and continuous service operation.

We ChatWork have achieved scalable and high availability service in our product called ChatWork Webhook, which was released in November 2017, using Apache Kafka, Akka HTTP, Akka Streams Kafka, Kubernetes.

In this session, I will share how we have achieved high performance and stability in Chatwork Webhook. It would be happy for me if this session would help your service development in future.
