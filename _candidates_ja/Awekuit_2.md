---
name: awekuit・小椋 友芳
title: "Akka Streams Kafka と Kafka Streams を両方運用している話"
length: 40
audience: Intermediate
language: Japanese
twitter: awekuit,tomoyoshi_ogura
github: awekuit,tarugo07
icon: https://pbs.twimg.com/profile_images/590112328756015104/kcSN89Am_400x400.jpg
organization: Chat Work 株式会社
tags:
  - Big Data / Fast Data
  - Best Practices
suggestions:
  - Akka にも Kafka にも興味のある方
  - Reactive な Fast Data 処理に興味のある方
---
2016年に開発したChatWork のチャットメッセージングマイクロサービスは、Akka HTTP, Akka Streams をベースに Kafka のイベント処理に Kafka Streams を使用しました。
2017年に開発したWebhookマイクロサービスは、同じくAkka HTTP, Akka Streams をベースに Kafka のイベント処理は Akka Streams Kafka (旧名 Reactive Kafka) を使用しました。
現在どちらもプロダクションで稼働していますが、なぜ使い分けているのか？ 何が違うのか？ をお話しします。
