---
title: "Benchmarking Postgres 17 vs 18"
url: "https://planetscale.com/blog/benchmarking-postgres-17-vs-18"
date: "2025-10-14"
author: "Ben Dicken"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Postgres 18 released a few weeks ago, and there's plenty of hype around the improvements it's bringing. Most notably, Postgres 18 introduces the io_method configuration option , allowing users more control over how disk I/O is handled. Setting this to sync results in the same behavior as 17 and earlier versions.
