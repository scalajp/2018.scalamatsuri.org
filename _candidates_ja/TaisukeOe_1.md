---
name: Taisuke Oe
title: "『暗黙』とうまく付き合うためのTips"
length: 40
audience: Beginner
language: Japanese
twitter: OE_uia
github: taisukeoe
icon: https://secure.gravatar.com/avatar/25fb3e7054e52e524817044853c2d4c3
organization: 
tags:
  - Best Practices
  - Intro to Scala
suggestions:
  - 暗黙に対して苦手意識のある人
  - 暗黙をもっと使いこなしたい人
slide_url: https://www.slideshare.net/TaisukeOe/how-to-get-along-with-implicits-91008535
youtube: https://youtu.be/ZKFIqwGp_B4
---
Scalaには『暗黙』というキーワードがあります。
ライブラリ設計者は暗黙の引数をうまく取り入れることで、
簡潔かつ柔軟、そしてコンパイル時にチェックされる安全なAPIを設計できます。

その一方で初学者にとって、暗黙の引数を含むAPIの使い方は、ちょっと学びにくいと感じることでしょう。
自分の使いたい暗黙の値の定義場所を調べるにはどうしたら良いのでしょうか?
あるいは、 自前のデータ型に対する暗黙の値を定義するベストの方法は？

このトークでは、暗黙にまつわるつまずきどころを出来るだけ一般化し、その対処法について解説します。
基本的に予備知識は必要としないように努めますが、暗黙の値の(自動)導出など、少し難易度の高い話題も触れます。
