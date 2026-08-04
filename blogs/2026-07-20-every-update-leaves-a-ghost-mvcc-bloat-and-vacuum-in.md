---
title: "Every UPDATE Leaves a Ghost: MVCC, Bloat, and VACUUM in PostgreSQL"
url: "https://planetscale.com/blog/postgresql-mvcc"
date: "2026-07-20"
author: "Jan Nidzwetzki"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Imagine running a big SELECT * on the order table while another process updates the same records concurrently. Your query completes displaying the original data, and the other sees successful data modification. This is Multi-Version Concurrency Control (MVCC), a technique where the database creates new copies of rows instead of overwriting them.
