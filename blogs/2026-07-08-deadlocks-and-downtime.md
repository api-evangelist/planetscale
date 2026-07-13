---
title: "Deadlocks and downtime"
url: "https://planetscale.com/blog/deadlocks-and-downtime"
date: "2026-07-08"
author: "Simeon Griggs"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Every second* of every day, your Postgres database could be hunting with intent to kill. *or whatever your deadlock_timeout setting is. Deadlocks happen when multiple transactions each hold a lock that the other needs, blocking both from proceeding.
