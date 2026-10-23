---
title: "What gets TOASTed in Postgres"
url: "https://planetscale.com/blog/what-gets-toasted-in-postgres"
date: "2026-10-12"
author: "Ahmed Darwich"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Insert 2,000 copies of the letter x into a table with an int ID and a text column, and Postgres stores all 2,000 bytes uncompressed. Insert 2,001, and Postgres compresses the value to 26 bytes with LZ4. That one extra byte is enough to trigger TOAST , the part of Postgres that compresses values once their row gets too big, and moves them out of the row when compressing isn't enough.
