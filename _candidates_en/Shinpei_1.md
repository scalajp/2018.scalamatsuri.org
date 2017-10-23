---
name: Shinpei a.k.a. Catshaped Gramophone
title: "Building native apps with Scala.js"
length: 40
audience: Intermediate
language: Japanese
twitter: neko_gata_s
github: Shinpeim
icon: https://pbs.twimg.com/profile_images/665564007474946048/xQADoQ5B_400x400.jpg
organization: MEDIROM Inc.
tags:
  - Best Practices
  - Software Design and Architecture
suggestions:
  - Those who want to develop GUI applications in Scala
  - Those who are interested in Scala.js practices
  - If you are tired of JavaScript
---
Today, the need for rapid development of desktop applications and mobile applications exist in order to provide a good UX. Toolkits for developing native GUI applications with JavaScript, such as ReactNative or Electron, fills such a need.

On the other hand, it is exceedingly difficult and cumbersome to manage complex state with dynamically typed language. In particular, it leads to bad developer experiences, forcing them to write applications with "tight" architecture (such as layered architecture in JavaScript) compared to writing in Swift or Kotlin.

From such a point of view, I wrote some applications, displayed below, using Scala.js and Electron or ReactNative for rapid development of the UI layer and robust development of the core layer.

- [NekogataDrumSequencer](https://shinpeim.github.io/ScalaJsDrumSequencer/web/build/) (web app)
- [Backlog](https://www.backlog.jp/) client app (desktop app powered by Vue.js)
- chord score editor(WIP) (iOS app powered by ReactNative)

In this session, I'll share the knowledge I obtained while writing those applications with Scala.js. The following content will be included.

- The fun part of developing native apps using Scala.js
- The painful part of developing native apps using Scala.js
- Suggestions on how to isolate Scala.js from JavaScript in our codes
- Application architecture that makes use of both the good parts of JavaScript and of Scala
