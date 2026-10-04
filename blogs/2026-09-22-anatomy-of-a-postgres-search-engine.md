---
title: "Anatomy of a (Postgres) search engine"
url: "https://planetscale.com/blog/anatomy-of-a-postgres-search-engine"
date: "2026-09-22"
author: "Patrick Reynolds"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Databases use indexes to make queries fast. Rather than check every row in a table for a matching value, look up that value in an index and seek directly to the right rows. Most database indexes are b-trees or b+trees , which sort a column's values in a total order and can quickly find matching values by exact value, a range of values, or a prefix.
