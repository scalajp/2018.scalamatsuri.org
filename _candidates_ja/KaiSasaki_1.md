---
name: 佐々木 海
title: "Spark 上で動くディープラーニングフレームワークを実装することで学んだこと"
length: 40
audience: Intermediate
language: Japanese
twitter: yotchang4s
github: yotchang4s
icon: https://www.gravatar.com/avatar/dede7dcf77241349e1d130cd2363d858?s=200
organization: Software Engineer, Treasure Data
tags:
  - Big Data / Fast Data
  - Tools, Data Science / Machine Learning
  - Others
suggestions:
  - 処理系に興味がある人
  - Pythonに興味がある人
  - Scalaでパーザーコンビネーターの導入を検討してる人
---
Deep LearningのフレームワークとしてはTensorFlow, Caffe, Chainerなどが有名ですが、数学的な背景やフレームワーク特有の考え（計算グラフ、Autograd）が必要ということもあり実装への敷居は若干高く感じられています。またそれらをスケールするように分散システムとして作るというのは更に難しいものになります。
Apache Sparkは近年最も活発に開発されている分散フレームワークのひとつでScalaで書かれています。このセッションではSparkを使って、シンプルなDeep Learningフレームワークを一から作ってみて感じた分散Deep Learningの勘所をお話します。内容はSpark上での実装詳細に加えて、スケールする勾配法やモデルの同期といった分散Deep Learningの概念的な話もします。

- Model ParallelismとData Parallelism
- オペレータとテンソル
- 非同期的な勾配法
- モデルの同期、パラメタサーバ
