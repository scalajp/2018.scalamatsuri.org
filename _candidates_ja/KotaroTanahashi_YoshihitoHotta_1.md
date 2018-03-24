---
name: 棚橋 耕太郎, 堀田義仁
title: "Recursive Schemeを用いた量子アニーリングマシン専用言語(DSL)の開発"
length: 10
audience: Intermediate
language: Japanese
twitter: 
github: 
icon: https://pbs.twimg.com/profile_images/1154146189/1029656369_dsc08417_400x400.jpg
organization: リクルートコミュニケーションズ
tags:
  - Functional Programming
  - Tools
  - Data Science / Machine Learning
suggestions:
  - 最適化問題をScalaで解きたい人
  - 量子アニーリングに興味がある人
slide_url:
youtube: https://youtu.be/wYnqtwvfzos
---
弊社では早稲田大学やカナダのD-Wave Systems Inc.と量子アニーリング(QA)に関する共同研究を行っています。
QAマシンで問題を解くためには、問題をQUBOと呼ばれる特別な形で表現し、ハードウェアの構造に合わせてマップする必要があります。
QAマシンのサイズは年々大規模化しており、この変換作業を毎回一から実装することは難しくなっています。
そこで、ScalaベースのQA専用DSLを開発することで以下の実現を試みました。

* 解きたい最適化問題を関数の組み合わせによって構造的、抽象的に記述できるようにする。
* 最適化問題の抽象的な表現の中に、回路のレイアウト最適化情報も自然な形で取り入れることができる。

かつてハードウェア記述言語の登場で大規模な集積回路の開発が容易になったように、ScalaベースのDSLによってQAのソフトウェア開発の生産性が向上すると期待しています。
