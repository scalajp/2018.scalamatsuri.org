---
name: Daniela Sfregola
title: "Easy and Efficient Data Validation with Cats"
length: 40
audience: Beginner
language: English
twitter: DanielaSfregola
github: DanielaSfregola
icon: /img/candidates/DanielaSfregola.png
organization: Daniela Tech LTD / Director
tags:
  - Functional Programming, Best Practices
suggestions:
  - People who want to know what are the pros and cons of different ways of validating data
---
Often when we create a client/server application, we need to validate the requests: can the user associated with the request perform this operation? Can they access or modify the data? Is the input well-formed?

When the data validation component in our application is not well designed, the code can quickly become not expressive enough and probably difficult to maintain. Business rules don't help, adding more and more requirements to add in our validation, making it more and more complex to clearly represent and maintain. At the same time when the validation fails, it should be fairly straightforward to understand why the request was rejected, so that actions can be taken accordingly.

This talk introduces Cats, a Scala library based on category theory, and some of its most interesting components for data validation. In particular, we'll discuss some options to achieve efficient and expressive data validation. We will also argue that, compared to other options in the language, Cats is particularly suited for the task thanks to its easy-to-use data types and more approachable syntax. 

Throughout the talk, you will see numerous examples on how data validation can be achieved in a clean and robust way, and how we can easily integrate it in our code, without any specific knowledge of category theory.
