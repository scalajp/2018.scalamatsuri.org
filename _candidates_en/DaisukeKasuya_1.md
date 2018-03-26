---
name: Daisuke Kasuya (daiksy)
title: "Lessons learned from operating a Scala-based system for 3 years"
length: 40
audience: Intermediate
language: Japanese
twitter: daiksy
github: daiksy
icon: https://gravatar.com/avatar/4dd89003cc8fe9f21d67b0c99b773436?s=256
organization: Hatena, Inc. Mackerel team
tags:
  - DevOps
  - Others
suggestions:
  - Those interested in Scala-based production systems
  - Those thinking about creating a new system in Scala
  - Those interested in operating a homegrown system
slide_url: 
youtube: https://youtu.be/tgqUirSkgmQ
---
It's been three years since the official rollout of Mackerel, a service that my team at Hatena builds using Scala on the server-side.

Here are some of the things that happened while we operated the system for three years.

- Tracking version upgrades of frameworks and libraries that we use.
- Deprecating some of the provided features, and subsequent removal of the source code.
- Tackling technical debts.
- Expanding hardware infrastructure following the system growth.

In this session, I would like to share how we tackled these problems and the lessons learned through operating Scala-based production system Mackerel for three years.
