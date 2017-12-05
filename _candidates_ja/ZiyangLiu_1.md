---
name: Ziyang Liu
title: "階層的構成(config)のスケーラブルな管理"
length: 10
audience: Beginner
language: English
twitter: 
github: zliu41
icon: https://avatars3.githubusercontent.com/u/6342538?s=400&v=4
organization: Software Engineer at Facebook
tags:
  - Big Data / Fast Data
  - Tools
  - Software Design and Architecture
suggestions:
  - 大規模かつ複雑なソフトウェアフレームワークの開発者
---
大企業のソフトウェアフレームワークは、多くの場合、大きな階層をなすオブジェクト群の構成(config)を管理する必要があります。
例えば、ワークフローサービスは、所有者、タイプ（ストリーミング、バッチなど）、環境（dev、prodなど）など、さまざまな方法でグループ化できるさまざまなワークフローとオペレータを管理およびスケジュールします。
階層内のさまざまなオブジェクトは、しばしば共有プロパティと固有プロパティの両方を持ちます。

この短いトークでは、Scalaの型システムを利用して最小限の冗長性でスケーラビリティと型安全性を実現するために、Scalaの構成(config)の階層を効果的に管理する方法について説明します。
