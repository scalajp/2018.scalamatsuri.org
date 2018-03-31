---
name: かとじゅん(@j5ik2o)
title: "リアクティブDDD実践入門"
length: 40
audience: Intermediate
language: Japanese
twitter: j5ik2o
github: j5ik2o
icon: https://pbs.twimg.com/profile_images/634548604443607040/3XbAnLJx_400x400.jpg
organization: ChatWork株式会社 テックリード
tags:
  - Software Design and Architecture
suggestions:
  - AkkaやDDDに興味がある方
slide_url: https://speakerdeck.com/j5ik2o/introduction-to-the-practice-reactive-ddd
youtube: https://youtu.be/o04DRRLiAw0
---
リアクティブシステムとドメイン駆動設計を組み合わせることがリアクティブDDDです。ChatWorkではすでにAkkaをフル活用した同様のシステムが運用されており、その経験から得られた知見を元に新しいDDDの設計スタイルを提案します。

主なトピックは以下です。  
- CQRS+Event Sourcingベースにしたアーキテクチャ構造の全体像  
- 集約としてのアクターと永続化されるドメインイベント  
- akka-httpのルート・ユースケース・集約アクタを一つのランナブルグラフに合成する方法  
- ReadModelUpdaterとDAOの実装  
- 耐障害性のためのBackOffSupervisorとCircuitBreaker  