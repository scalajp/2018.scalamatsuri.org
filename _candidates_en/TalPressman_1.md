---
name: Tal Pressman
title: "Copying from Kubernetes for fun and profit"
length: 40
audience: Intermediate
language: English
twitter: talpr
github: talpr
icon: https://pbs.twimg.com/profile_images/3006003401/c931e238f821bb8ffe86fc66bef287ef_400x400.jpeg
organization: Software Architect, NEX Traiana
tags:
  - Software Design and Architecture
  - Others
suggestions:
  - People who want to learn a little about the Kubernetes design, and how to borrow from it in their own applications.
---
Managing thousands of inter-dependent resources is not a simple problem. Luckily, this problem was already solved by Kubernetes.

This talk will explore the problem of managing a large number of resources, that each have their own separate lifecycle and dependencies, and walk through the design of an internal resource management system that borrows heavily from Kubernetes, implemented in Scala and Akka.