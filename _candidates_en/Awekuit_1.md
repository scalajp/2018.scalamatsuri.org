---
name: awekuit
title: "An approach to archive important and sensitive non-disruptive operation using Akka Streams and Kubernetes"
length: 40
audience: Intermediate
language: Japanese
twitter: awekuit
github: awekuit
icon: https://pbs.twimg.com/profile_images/590112328756015104/kcSN89Am_400x400.jpg
organization: Chat Work
tags:
  - Tools
  - Best Practices
suggestions:
  - People who need non stop operation on production DB
  - People who are interested in Akka and modern container orchestration tools
---
ChatWork migrated our chat messaging system from PHP to Scala and our database from Aurora to HBase at the end of 2016.
After the data migration, adjustment was made on the production data and it was not disruptive. We adopted Akka Streams rather than Spark, which was used in the data migration.
We achieved non-disruptive adjustment for 2 billion records of the production data even though we had experienced big change from RDBMS to NoSQL and started new DB operation.
In this talk, I will share how high throughput, flexibility, extensibility of Akka Streams overcame the challenge above. In addition, I will share how we completed the sensitive operation safely by dynamic throttling control using a combination of Akka Streams and Kubernetes.
