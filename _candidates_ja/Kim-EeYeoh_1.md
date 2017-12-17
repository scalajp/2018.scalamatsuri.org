---
name: Kim-Ee Yeoh
title: "圏論を用いた美しい乱数: なぜ State モナドが理想ではなく、どのモナドが優れているのか"
length: 10
audience: Intermediate
language: English
twitter: ky3atamo
github: 
icon: http://ruby.id/images/conf/2017/abdullah-pic.jpg
organization: 
tags:
  - Functional Programming
  - Best Practices
  - Microservices
suggestions:
  - バグの入り込みづらいピッタリとした抽象化がほしい Scala 開発者
---
乱数生成は通常 State モナドを用いて行われる。しかし、State モナドはクライアントアプリにシードへの書き込みアクセスを与えてしまうので、機能過剰だ。そのため、アプリは同じ乱数の数列を繰り返してしまったり、間違えて 9, 9, 9 と延々と返してしまう可能性がある。

理想的には、クライアント側は乱数をリードオンリーにしたい。シードの設定は別のレイヤーで行われる。

RNG のインターフェイスを圏論的に正しくモデル化するとどうなるだろうか?

このトークは 3つの利点を提起する。第一は答えが分かることだ。第二は Free モナドの実例を見れることだ。最後に、双対性 (duality) を使ってこの理論を覚えるコツを紹介する。
