---
name: Marcin Matuszak
title: "あなたの工具箱にお手軽工具はいかが？ ~Lenses/Zippers/State~"
length: 40
audience: Intermediate
language: English
twitter: marcinmatuszak
github: 
icon: https://pbs.twimg.com/profile_images/843532549720854528/0Q8YKVZO_400x400.jpg
organization: Data Engineer / Ryanair 
tags:
  - Functional Programming
suggestions:
  - LensesやZippers、Stateモナドがどんな働きをするのか、組み合わせて使う方法を知りたい人
  - 巨大なイミュータブルオブジェクトと一緒に使う必要がある
  - もっと高度な話題にのめり込みたい
---
関数型プログラミング言語の一番のウリは、不変性です。
一見ほとんど思考を要しないものに見えます。しかし、根深い入れ子構造を _変更_ する必要がある時には、問題が出てきます。

今回のプレゼンテーションの狙いは、イミュータブルなオブジェクト(値クラスやコレクション)を効率よく働かせる方法を紹介することです。
プレゼンテーションの間、 lensesやzippersといった有意義な2つの主なアプローチに着目します。

私の２つ好きなライブラリ(monocleやcirceとcats)を用いた幾つかの実践的な例を元にちょっとした私見を説明します。
