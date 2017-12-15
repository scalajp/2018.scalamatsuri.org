---
name: phenan
title: "Scala上のDSLを自動生成する"
length: 40
audience: Intermediate
language: Japanese
twitter: phenan
github: phenan
icon: https://pbs.twimg.com/profile_images/663178783/enemy4_bigger.png
organization: 東京大学
tags:
  - Tools
suggestions:
  - Scalaで良い感じのAPIを持つライブラリを作ってみたい人
  - Scalaの型システムの応用に興味がある人
  - 「型検査時構文解析」という言葉に興味を引かれた人
---
Scala では、メソッドチェーン、implicits、各種省略記法などを活用して強力なDSL風のAPIを作ることができます。  
例えば、ScalaTest はテストを自然言語風に記述するAPIを提供していますし、ScalikeJDBC はメソッドチェーンを使った SQL 風の記法を提供しています。  
しかしこのような優れたAPIを正しく実装するのは実はかなり大変です。

そこで、作りたいDSLの文法からそのようなAPIを自動的に生成するためのツールを作成しました。  
このツールを使えば誰でも簡単に自然言語風のAPIや既存のDSLに似せたAPIをScala上で実装することができます。  
内部的には、Scalaの型検査を利用してLALR構文解析器を実装するということをしています。  
このセッションでは、このツールの紹介と、その実装方法について簡単にお話します。