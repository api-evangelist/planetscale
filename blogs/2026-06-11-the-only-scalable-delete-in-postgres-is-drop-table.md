---
title: "The only scalable delete in Postgres is DROP TABLE"
url: "https://planetscale.com/blog/the-only-scalable-delete"
date: "2026-06-11"
author: ""
feed_url: "https://planetscale.com/blog"
---
Large DELETEs add work instead of reclaiming it. Structure your database so deletion becomes DROP TABLE or TRUNCATE.
