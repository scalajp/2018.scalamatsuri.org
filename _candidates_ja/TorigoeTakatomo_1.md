---
name: 鳥越貴智（piyo7）
title: "量子コンピュータをScalaでかわいくシミュレーションしてみよう♪"
length: 40
audience: Beginner
language: Japanese
twitter:
github: piyo7
icon: https://www.gravatar.com/avatar/e650d601c28f8accb2eeacca8fc2b092?s=200
organization: 株式会社サイバーエージェント　サーバーサイドエンジニア
tags:
  - Intro to Scala
  - Others
suggestions:
  - 量子コンピュータと聞いてワクワクする方
  - 数値計算の実装に興味のある方
slide_url: https://www.slideshare.net/TaokatomoTorigoe/lets-simulate-a-quantum-computer-with-pretty-scala
youtube: https://youtu.be/eFT2MIcZZeA
---
夢の超並列計算機、量子コンピュータの実用化が熱を帯びていますね。
量子の世界というと「シュレディンガーの猫」のようなSF話も面白いものですが、プログラマーとしてはまずアルゴリズムに興味があるところではないでしょうか？
実のところ、ゲート方式の量子コンピュータで動くアルゴリズムは、複素数の行列計算さえできれば組めてしまうのです！

しかし、複素行列を手計算するのは、なかなか骨が折れますね。
なるべく数式に近い表現で、しかも型安全に、色々な演算をサクッと実装できる言語があれば、幸せになれそうではないでしょうか？
ああ。そんな、かわいらしい言語を、一つ知っています。そうです、我々の共通言語は、Scalaですから！

ということで量子コンピュータを題材に、拡張メソッドや型レベル整数といったテクニックと、その指針をご紹介します♪
