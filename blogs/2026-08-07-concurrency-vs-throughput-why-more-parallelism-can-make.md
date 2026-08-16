---
title: "Concurrency vs. Throughput: why more parallelism can make databases slower"
url: "https://planetscale.com/blog/concurrency-vs-throughput-vitess-mysql"
date: "2026-08-07"
author: "Liz van Dijk"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Not long ago we watched a production MySQL database melt down for sixteen minutes. The errors started as a trickle, a handful per minute, then fed on themselves: minute errors/min queries/s 0 5 15,000 2 60 3,900 4 300 2,500 6 550 2,000 8 900 1,900 10 1,400 1,500 12 700 1,700 14 250 2,000 16 0 2,500 18 0 8,500 The trigger was fairly mundane: A batch job opened a transaction against a hot table, took row locks, and then held them for fifteen minutes without committing. A common application bug, the kind that eventually sneaks into many large codebases.
