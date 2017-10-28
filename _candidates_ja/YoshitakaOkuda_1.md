---
name: 奥田 佳享
title: "ScalikeJDBC streams開発を通して学んだFlow API実装のポイント"
length: 40
audience: 中級者
language: 日本語
twitter: https://twitter.com/yoskhdia
github: https://github.com/yoskhdia
icon: https://pbs.twimg.com/profile_images/814301502516826112/tkeIfq1H_400x400.jpg
organization: Supership株式会社
tags:
  - Best Practices
  - Software Design and Architecture
  - Others
suggestions:
  - Flow API(Reactive Streams)の内部を知って使いたいと思う人
  - Flow APIを実装したいと考えている人
  - ScalikeJDBC streamsがどう実装されているか知りたい人
---
Java9にFlow APIが新たに加わっていることをご存知でしょうか。Flow APIはReactive Streams仕様と1対1に対応する、非同期ストリーム処理の標準仕様です。これは異なる複数のコンポーネント間の接続を共通化できるものです。既にAkka Streamsをはじめとして、AWS Java SDKでも実装が行われるなど、各種ライブラリの対応が進んでいます。しかし、Flow APIは仕様(Specifications)を定めるのみで、具体的な実装は含まれません。
Flow APIとは何かという概論は他に譲るとして、本セッションでは、ScalikeJDBC Streamsモジュールの実装を通して得た、Flow API(Reactive Streams)のより具体的な実装方法について解説します。
