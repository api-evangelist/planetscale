---
title: "The dangers of Postgres subtransactions"
url: "https://planetscale.com/blog/the-dangers-of-postgres-subtransactions"
date: "2026-08-11"
author: "Jan Nidzwetzki"
feed_url: "https://planetscale.com/blog/rss.xml"
---
A single transaction that accumulates numerous subtransaction IDs can significantly reduce throughput across an entire PostgreSQL cluster. It can also stop a new read replica from accepting queries, even as the replica continues to replay WAL. If you add read replicas on demand during a load spike, a replica that cannot open for reads provides no extra capacity.
