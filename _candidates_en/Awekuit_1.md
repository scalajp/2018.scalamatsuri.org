---
name: awekuit
title: "An approach to archive important and sensitive non-disruptive operations using Akka Streams and Kubernetes"
length: 40
audience: Intermediate
language: Japanese
twitter: awekuit
github: awekuit
icon: https://pbs.twimg.com/profile_images/590112328756015104/kcSN89Am_400x400.jpg
organization: ChatWork
tags:
  - Tools
  - Best Practices
suggestions:
  - People who need non-stop operations on production DB
  - People who are interested in Akka and modern container orchestration tools
---
ChatWork migrated our chat messaging system from PHP to Scala and our database from Aurora to HBase at the end of 2016.
After the data migration, adjustments were made on the production data and they were not disruptive. We adopted Akka Streams rather than Spark, which was used in the data migration.
We achieved non-disruptive adjustment for 2 billion records of production data even though we had experienced big changes from RDBMS to NoSQL and started a new DB operation.
In this talk, I will share how the high throughput, flexibility, and extensibility of Akka Streams overcame the challenges above. In addition, I will share how we completed this sensitive operation safely by dynamic throttling control using a combination of Akka Streams and Kubernetes.
