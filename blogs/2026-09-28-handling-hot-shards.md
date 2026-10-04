---
title: "Handling hot shards"
url: "https://planetscale.com/blog/hot-shards-hotter-tenants"
date: "2026-09-28"
author: "Simeon Griggs"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Since the launch of Neki we've talked a lot about sharding with basic examples to demonstrate how Neki splits a table's rows evenly across shards. Neki's router reads your data topology to handle the placement of writes and to find the correct shard for reads. But life in production is never so simple.
