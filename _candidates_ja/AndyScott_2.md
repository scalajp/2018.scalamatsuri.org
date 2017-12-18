---
name: Andy Scott
title: "詳解iota"
length: 40
audience: Advanced
language: English
twitter: andygscott
github: andyscott
icon: https://pbs.twimg.com/profile_images/941929774250827776/9hbZ-_8b_400x400.jpg
organization: Humanoid Extraordinaire @ Stripe
tags:
  - Functional Programming
  - Microservices
  - Others
suggestions:
  - 余積(coproduct)やFreeモナドなどの関数型プログラミング言語の概念に既に慣れている人
---
Freestyleのiotaは、余積(coproduct)を最適化した高パフォーマンスの関数型プログラミングライブラリです。
そのメリットとして第一に挙げられるのは、FreestyleにおけるFreeモナドの高速な実行(evaluation)です。
しかしながら、iotaにはFree以外にも使える隠れた機能が沢山あるのです。

エラーハンドリングや汎用的な型クラス導出のようなその他の関数型プログラミングのパターンについて触れながら、iotaの現在(及び近いうちに導入される）機能について見てみましょう。

それに加え、iotaの裏側の仕組みや、iotaの実装に使われているマクロについて紹介したいと思います。
