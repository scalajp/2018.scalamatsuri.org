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
The practice of Infrastructure-as-Code has now been widely accepted. Even in the cloud infrastructure, it has become commonplace to use a code-based configuration management tool such as AWS CloudFormation. On the other hand, CloudFormation has had problem with ease of writing and maintainability due to its adoption of JSON. This lead many to create Domain Specific Languages (DSLs) that generated templates. These DSLs helped in improving expressiveness and readability, but they were never sufficient to support the description of complex logic required for large-scale systems.

To overcome this issue, we are developing a new opensource DSL that can update complex cloud infrastructure in a safe manner with the support of the static type system of Scala. In this talk, I'd like to share this DSL's features, design philosophy, and practical use cases.
