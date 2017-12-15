---
name: 安田裕介 @TanUkkii007
title: "チャットワークのメッセージシステムを支える新分散ID発行器の内部"
length: 40
audience: Intermediate
language: Japanese
twitter: TanUkkii007
github: TanUkkii007
icon: https://avatars0.githubusercontent.com/u/2936722?s=460&v=4
organization: プロダクト開発部/開発者
tags:
  - Best Practices
  - Software Design and Architecture
  - Microservices
suggestions:
  - 分散合意アプリケーションでのアクタープログラミングの親和性を知りたい人
- 国内最大のビジネスチャットサービスでの分散IDの使われ方を知りたい人
- Akkaで分散システムを構築したい人
---
チャットワークは2017年の春にメッセージのIDを64bitに移行しました。この新IDはTwitter snowflakeのような、旧来のRDBのIDと互換性を保ちつつも、分散発行が可能なIDとなっています。分散ID発行器は１台で秒間40000のIDを発行でき、旧来の発行器と比べてレイテンシを10msほど改善しました。分散ID発行器ではAkkaとZooKeeperを用いました。ZooKeeperアプリケーションは  
1.受動的で、  
2.状態機械であり、  
コネクションの喪失などの3.エラーに常に対処し、  
またセッションの期限切れの際に4.状態を破棄する  
必要があります。これらはまさにアクターで自然に実装できます。またアクターの位置透過性とAkkaのマルチJVMテストキットは分散環境でのテストを容易にします。この発表では新ID発行器の内部を、アクターとZooKeeperの組み合わせの観点から解説します。