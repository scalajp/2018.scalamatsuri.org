---
name: Tomer Gabel
title: "中の人なんていない: CPU 編"
length: 40
audience: Intermediate
language: English
twitter: tomerg
github: holograph
icon: https://en.gravatar.com/userimage/2348772/5a33305526710f6c1ee2da68004d8b8c.jpeg
organization: Wix
tags:
  - Software Design and Architecture
  - Others
suggestions:
  - 「システム言語開発者」以外の皆で、自分のコードがどう動作しているのかちゃんと知りたい人
---
ソフトウェアを書いていると完全にコントロールを握っているかのような淡い幻想を抱いてしまいがちだ。それは何層にも渡るレイヤー化と抽象化が大量の複雑さを隠蔽するのに成功しているからとも言える。しかし、複雑さが必然的に漏れたときは、内部で何が起こっているかを知っていることが得になる。

このトークでは、レイヤーをいくつか取り除いて「エンジン」部分である CPU を覗いてみる。全てのアプリケーション、たとえそれが高レベルな Scala であっても、最終的にはプロセッサでマシンコードを実行する。そのため、JVM はメモリモデルを持ち、規模が大きくなるとメモリのレイアウトが効いてくる。また、なぜ通常は無視して安心して作業してもいいのかも解説する。
