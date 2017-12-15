---
name: 小椋 友芳
title: "Scalaでスケーラブルかつハイアベイラビリティなサービスを開発するためのヒント"
length: 40
audience: Beginner
language: Japanese
twitter: tomoyoshi_ogura
github: tarugo07
icon: https://pbs.twimg.com/profile_images/941557571831324673/_prrpo1D_400x400.jpg
organization: ChatWork株式会社
tags:
  - Software Design and Architecture
  - Microservices
  - Others
suggestions:
  - Scalaでのサービス開発に興味がある人
---
無限に発生する大量のデータをリアルタイムに処理していくサービスの開発では様々な課題が発生します。  
特にサービスとして継続的に運用するために高い安定性を保ちながら、処理のスループットを向上させることは達成がとても困難な課題ではないでしょうか？

チャットワークが11月にリリースしたChatWork WebhookはApache KafkaやAkka HTTP、Akka Streams Kafka、Kubernetesなどを採用することでスケーラブルかつハイアベイラビリティなサービスを実現できました。

このセッションではChatWork Webhookでサービスのパフォーマンスや安定性の向上のために実際に行った取り組みを紹介します。  
紹介する実例を皆様の今後のサービス開発のヒントとしていただければと思います。