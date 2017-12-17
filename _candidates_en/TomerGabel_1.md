---
name: Tomer Gabel
title: "An Abridged Guide to Event Sourcing"
length: 40
audience: Beginner
language: English
twitter: tomerg
github: holograph
icon: https://en.gravatar.com/userimage/2348772/5a33305526710f6c1ee2da68004d8b8c.jpeg
organization: Wix
tags:
  - Software Design and Architecture
  - Microservices
suggestions:
  - Working engineers scratching their heads when implementing such systems. 
  - A full blown example in Scala will be provided (although code isn't really a major part of this talk, it's more architecture-focused).
---
Although event sourcing (and sister pattern CQRS) has been gaining traction in recent years, many engineers are struggling when implementing it for the first time. While there's plenty of material on the subject, most of it is too broad or theoretical, and engineers often end up having to rediscover suitable approaches and techniques.

This talk introduces practical aspects of building such systems learned from our experiences at Wix. We'll walk through the design and implementation of a simple event-sourced system, covering the event model, underlying persistence and suitable code layering.
