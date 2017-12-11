---
name: Jasper van Zandbeek
title: "http4s と doobie を用いた純粋関数型マイクロサービス"
length: 40
audience: Beginner
language: English
twitter: jaspervanzand
github: jaspervz
icon: https://avatars2.githubusercontent.com/u/2083625
organization: Freelance Scala Developer
tags:
  - Microservices
suggestions:
  - マイクロサービスの経験が全く無いか少しあって、関数型な方法で書いてみたい人。
---
関数型なプログラマーとしては、純粋関数を合成して、副作用に煩わされずに、コードで何が起こっているのかを筋道立てて考えたい。

しかし、純粋関数をマイクロサービスと合成するにはどうすればいいだろうか? マイクロサービスは、おうおうにして Scala Future を用いて作成されているので、根本的に非純粋である。これは、純粋性を妥協しなければいけない分野ということなのだろうか? もしくは、他に代替案はあるのだろうか?

http4s と doobie を併用することで、純粋関数型なマイクロサービスを構築することが可能で、副作用はアプリケーションの境界まで押し出すことができる。このトークでは、初学者向けにこれを解説する。
