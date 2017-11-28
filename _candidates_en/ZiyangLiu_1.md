---
name: Ziyang Liu
title: "Managing Hierarchical Configurations Scalably"
length: 10
audience: Beginner
language: English
twitter: 
github: zliu41
icon: https://avatars3.githubusercontent.com/u/6342538?s=400&v=4
organization: Software Engineer at Facebook
tags:
  - Big Data / Fast Data
  - Tools
  - Software Design and Architecture
suggestions:
  - Developers of large and complex software frameworks
---
Software frameworks in large enterprises often have to manage configs for a large hierarchy of objects. For example, a workflow service manages and schedules a variety of workflows and operators, which can be grouped in multiple ways, e.g., by their owners, by types (streaming, batch, etc.), or by environments (dev, prod, etc.). Different objects in the hierarchy often have both shared and unique properties.

This brief talk will outline an approach to effectively manage a hierarchy of configs in Scala, utilizing Scala's type system to achieve scalability and type safety with minimal redundancy.
