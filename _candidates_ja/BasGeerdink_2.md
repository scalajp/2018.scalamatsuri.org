---
name: Bas Geerdink
title: "Analytics ad ING - データ駆動の金融企業を作った理由、実態及び方法"
length: 40
audience: Intermediate
language: English
twitter: bgeerdink
github: geerdink
icon: https://pbs.twimg.com/profile_images/911184285830348800/q0O6D7iA_400x400.jpg
organization: Technology Lead at ING
tags:
  - Big Data / Fast Data
  - Best Practices
  - Data Science / Machine Learning
  - DevOps
  - Software Design and Architecture
suggestions:
  - Big Data及びFast Dataを扱っている金融系大企業について学びたいエンジニア、マネージャ及びアーキテクト
---
(字数超過のため、和訳せず原文のまま掲載しています)
ING is a Data-Driven Experimental Enterprise, which is heavily investing in big data, analytics and streaming processing. As in many other enterprises, we deal with a large variety of data sources. The amount of data which must be handled goes beyond the computing performance of single machines, and vertical scalability is hardly an option. For this specific reason we are moving towards a scenario where machines are grouped into clusters and data is handled by distributed processing systems.

Important building blocks in our journey are the state-of-the-art Data Lake, and the Streaming Data Platform. The data lake, built around Hadoop and IBM PDA, replaces several enterprise data warehouses and is the central repository for all types of data, supporting various types of queries for our stakeholders' demands. Data is also being handled more often than not as streams and we are working with Flink and Kafka to provide faster, more reactive and up-to-date user experiences and journeys. Finally, machine learning is aiding traditional SQL to provide better insight when it comes to operational excellence, business processes, marketing and security applications.

In this talk, Bas will explain why ING is becoming more and more data-driven, and how we do it. He will share use cases, architecture, and technology choices.
