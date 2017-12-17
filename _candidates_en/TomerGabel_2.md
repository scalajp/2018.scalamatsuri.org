---
name: Tomer Gabel
title: "How shit works: the CPU"
length: 40
audience: Intermediate
language: English
twitter: tomerg
github: holograph
icon: https://en.gravatar.com/userimage/2348772/5a33305526710f6c1ee2da68004d8b8c.jpeg
organization: Wix
tags:
  - Software Design and Architecture
  - Others
suggestions:
  - All "non-system-language" developers that want to know a bit more about how their code actually gets executed.
---
Building software gives you the warm and fuzzy illusion of total control; this is the result of layers upon layers of successful abstractions hiding immense complexity. But when they inevitably leak, that's when knowing what's under the hood pays off.
  
In this talk we'll peel a few layers and take at our "car engine", the CPU. All applications, even in high-level Scala, end up executing machine code instructions on a processor; that is why the JVM has a memory model, why memory layout still matters at scale, and we'll show why you're usually free to ignore these and go about your job.
