---
title: "Poisoned Postgres connection pools"
url: "https://planetscale.com/blog/postgres-poisoned-connection-pools"
date: "2026-08-18"
author: "Josh Brown"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Did you know you can poison your Postgres connection pool? Most people have no idea what this means, but it could take down your entire database if you're not careful managing your connection pooler. An engineer's worst nightmare is waking up to a seemingly read-only database with no clear issue in sight.
