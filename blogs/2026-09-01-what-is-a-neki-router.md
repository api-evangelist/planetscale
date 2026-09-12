---
title: "What is a Neki router?"
url: "https://planetscale.com/blog/what-is-a-neki-router"
date: "2026-09-01"
author: "Andres Taylor"
feed_url: "https://planetscale.com/blog/rss.xml"
---
The core challenge in operating a sharded database is deciding which shard(s) should execute a query. Each query passes through two plans. The Neki router builds the first plan using the data topology to decide which shard(s) receive the work and how results from multiple shards should be handled.
