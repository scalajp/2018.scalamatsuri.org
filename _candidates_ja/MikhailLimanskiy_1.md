---
name: Mikhail Limanskiy
title: "BeanPuréeでJavaBeansをShapelessにしてみよう！"
length: 40
audience: Advanced
language: English
twitter: mike.limansky
github: limansky
icon: http://limansky.me/images/mikhail400x400.jpg
organization: 1-OFD
tags:
  - Functional Programming
  - Others
suggestions:
  - 1. Scalaを第一言語として使っているが、プロジェクトではJavaのコードもメンテすることがある人
  - 2. 型レベルプログラミングを使い始めたい人
---
時にScalaのプロジェクト内でJavaを使わざるを得ないことがあると思います。その場合、ScalaとJava別々のモデルを使うことになるかもしれません。例えば、Scalaのコード部分では可変なクラスを使いたくない場合や、JavaBeanで記述されたデータをcase classを期待しているScalaのライブラリへ渡したりする場合です。BeanPuréeは、そのようなJavaBeansにジェネリックなプログラミングをもたらすライブラリです。JavaとScalaのモデルを変換することができます。でも、ただ変換するだけにはとどまりません。このセッションでは、BeanPuréeとshapelessを使った型レベルプログラミングの例をいくつも紹介したいと思います。