---
title: "Massively parallel Postgres backups"
url: "https://planetscale.com/blog/massively-parallel-postgres-backups"
date: "2026-07-31"
author: "Ben Dicken"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Every 12 hours, a backup system must turn the entire state of a busy database into a consistent, encrypted snapshot, with no impact to production queries. Such backups are crucially important and simultaneously something that most engineers would rather never have to think about. Just make the backup work .
