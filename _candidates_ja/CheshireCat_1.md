---
name: チェシャ猫
title: "Haskell + Scala ハイブリッド開発大作戦"
length: 40
audience: Beginner
language: Japanese
twitter: y_taka_23
github: y-taka-23
icon: https://avatars2.githubusercontent.com/u/2419525
organization: ProofCafe
tags:
  - Functional Programming
  - Others
suggestions:
  - Haskell にハードルの高さを感じている Scala/Java プログラマ
slide_url: https://speakerdeck.com/ytaka23/operation-haskell-plus-scala
youtube: https://youtu.be/u9WACa-JRA4
---
本セッションでは、JVM 用 Haskell である Eta を利用して、Haskell/Scala 間のシームレスな連携を実現する技法を解説します。

Eta はモダンな Haskell コードに対してほぼ完璧な互換性を担保する一方、意味論として異質な Scala/Java ライブラリの呼び出しを巧妙にサポートしています。またコンパイル結果は JVM バイトコードになり、Scala プロジェクトの内側に Haskell 部分を組み込むことも容易です。まさに、それぞれの言語の「いいとこ取り」にうってつけだと言えるでしょう。

内容としては、Haskell の初歩から始めて、Haskell/Scala 間の相互呼び出しの仕組みや、実際のハイブリッドプロジェクトの構成を解説する予定です。予備知識は仮定しませんので、「Haskell ってなんか怖そう」と思っているあなたにこそオススメします。
