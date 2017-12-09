---
name: David van Geest
title: "Akka: Backend-for-Frontend パターンのズッ友 BFF!"
length: 40
audience: Intermediate
language: English
twitter: DWvanGeest
github: DWvanGeest
icon: https://avatars3.githubusercontent.com/u/947530?s=460&v=4
organization: Senior Software Engineer, PagerDuty Inc.
tags:
  - Best Practices
  - Software Design and Architecture
  - Microservices
suggestions:
  - Akka Steams や Akka HTTP に興味のある人
  - ライブ感のある UI に興味のある人
  - マイクロサービスのアーキテクチャに興味がある人
  - Backend-for-Frontend を作ってみたい人
---
PagerDuty社は APIを直接担うマイクロサービス群を開発してきた。これらのマイクロサービスは (たとえば認証など) 一般的なエッジの問題を取り扱う必要があり、またエンドユーザに簡単な形でデータを提供する必要がある。これらのデータは通常 HTTP リクエストに対するレスポンスとして返されるが、WebSockets を用いたライブなデリバリーも増加傾向にある。

Backends-for-Frontends (BFF) パターンはこの需要を埋めるものだ。このセッションの参加者は PagerDuty社がどのようにして BFF パターンを実装するかを習うことができる。API リクエストの代理とデータの集約には Akka HTTP を用い、Kafka からエンドユーザへのライブデータのデリバリーには Akka Streams を用いている。
