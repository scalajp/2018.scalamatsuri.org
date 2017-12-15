---
name: Jakub Kozłowski
title: "純粋関数型HTTPクライアント for Free"
length: 40
audience: Intermediate
language: English
twitter: kubukoz
github: kubukoz
icon: https://pbs.twimg.com/profile_images/905069106692546561/CUboQNLQ.jpg
organization: Scala developer, Scalac
tags:
  - Functional Programming
  - Tools
  - Software Design and Architecture
suggestions:
  - HTTPのAPIを使って副作用から解き放たれたアプリケーションを書きたいと思っている人
---
外部APIと接続することは、今や殆どのバックエンドサービスの一部となっています。本質的にHTTPの呼び出しは副作用を内包し、これまで副作用のあるプログラムのテストをしたことがある人はわかると思いますが、テストすることが苦痛であることが多々あります。どうにかして、外部サービスを純粋で関数型的な方法で統合し、テストをより簡単にすることは出来ないでしょうか？可能です。そうフリーモナドならね。

まず命令的なHTTPクライアントを段階を追って純粋関数型的なものへと変えていきます。そして、どのようにWebAPIクライアントに利用し、どれほどテストを他愛ないものに出来るかを紹介したいと思います。