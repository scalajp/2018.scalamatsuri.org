---
name: CHETANKUMAR KHATRI
title: "テラバイト以上のデータをApache SparkとScala DSLでプロダクションでスケールさせる"
length: 40
audience: Beginner
language: English
twitter: khatri_chetan
github: chetkhatri
icon: https://avatars0.githubusercontent.com/u/6836627?s=400&v=4
organization: Lead - Data Science at Accion labs.
tags:
  - Big Data / Fast Data
  - Functional Programming
  - Best Practices
  - Data Science / Machine Learning
  - Software Design and Architecture
suggestions:
  - Scalaにおける関数型プログラミングの基礎と、Javaについて理解している人 
  - Java / Scalaにおける並行プログラミングとマルチスレッドについて理解している人
  - Big Data及びFast Dataの領域で業務経験のある人、もしくは強い関心がある人
---
(字数超過のため、和訳せず原文のまま掲載しています)
Since Apache Spark became one of the leading top Apache community project with Scala, Requirement of scala skillset changed drastically at global level. As entire Apache Spark framework has been written in scala from ground, it’s real pleasure to understand beauty of functional Scala DSL with Spark.

This talk is intent to present :
- primary data structures (RDD, DataSet, Dataframe) usage in universal large scale data processing with Hbase (Data lake), Hive (Analytical Engine).
- We will go through importance of physical data split up techniques such as Coleanse, Partition, Repartition in Scaling TB’s of data with ~17 billions of transactional data as a use case / case study.
- Also, We will understand crucial part and very interesting way of understanding parallel & concurrent distributed data processing – tuning memory, cache, Disk I/O, Leaking memory, Internal shuffle, spark executor, spark driver etc.  
