---
name: Konrad `ktoso` Malawski
title: "あらゆるものを分散コンピューティングで扱おう(Akkaをつかって)"
length: 40
audience: Intermediate
language: English
twitter: ktosopl
github: ktoso
icon: https://scontent-nrt1-1.xx.fbcdn.net/v/t31.0-8/15626425_10202875601369012_2764589549729738273_o.jpg?oh=57591212f91d0b834b45ff9806e05ec8&oe=5A921F16
organization: Akka Team, Lightbend
tags:
  - Software Design and Architecture
  - Microservices
  - Others
suggestions:
  - 高性能・高信頼性のシステムに興味のある開発者、このセッションを聴講するのにAkkaに関する事前知識は必要はありません

---
Akkaの最近の動向や、Akka StreamsがリリースされReactive Streams(java.util.concurrent.Flow)がOpenJDK (Java 9)に含まれるという事実によって、
あなたはもしかするとAkkaの次の開発の焦点は何なのか？と考えているかもしれません。
実はAkkaの次の開発の焦点は、過去に行ったことのなかでまだ完成されていないものです。
すなわち、全てのAPIの中からより多くのものに型情報を追加することであり(Akka Streamsで実現されたように)、
そしてこれは安定したAkka Typed APIおよびそのAPIをStreamsとClusterに統合することによって可能になります。
別の言い方をすれば、ビルド時安全で、型検査を行うことが出来、back-pressureを扱うことができ、あなたのニーズによってスケールアウト・インすることができる
分散コンピューティングシステムを実現することです。
このセッションではAkkaのAPIの原則とAPIがどのように変遷してきたか、そして新しいAPIがどのようにあらゆるものを統合し、
リアクティブな分散コンピューティング環境に置くことが出来るかお話します。
