---
title: "What's new in Postgres 19"
url: "https://planetscale.com/blog/whats-new-in-postgres-19"
date: "2026-07-23"
author: "Ahmed Darwich"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Postgres has never had a great built-in way to shrink a bloated table. VACUUM identifies dead space for reuse, but doesn't return it to the operating system. VACUUM FULL and CLUSTER do, but they lock the table for the whole rewrite.
