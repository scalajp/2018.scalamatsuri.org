---
name: Mitsuhiro Shibuya (@m4buya)
title: "Type-safe CloudFormation DSL in Scala"
length: 40
audience: Intermediate
language: Japanese
twitter: m4buya
github: mshibuya
icon: https://avatars0.githubusercontent.com/u/486678?s=460&v=4
organization: Opt, Inc
tags:
  - DevOps
suggestions:
  - Those interested in cloud infrastructure
  - Those looking for new ways to utilize Scala
---
The practice of Infrastructure-as-Code has now been widely accepted, and even on the cloud infrastructure, it has become a commonplace to use a code-based configuration management tool, such as AWS ClouldFormation. On the other hand, CloudFormation has had problem with ease of writing and maintainability due to its adoption of JSON. This lead many to create Domain Specific Languages (DSLs) that generate templates. These DSLs help in improving the expressiveness and readability, but they were never sufficient to support the description of complex logic required for large-scale systems.

To overcome this issue, we are developing a new DSL in opensource that can update complex cloud infrastructure in a safe manner with the support of static type system of Scala. In this talk, I'd like to share its features, design philosophy, and practical use cases.
