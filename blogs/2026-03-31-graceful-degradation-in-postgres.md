---
title: Graceful degradation in Postgres
url: https://planetscale.com/blog/graceful-degradation-in-postgres
date: '2026-03-31'
author: Ben Dicken
feed_url: https://planetscale.com/blog/rss.xml
---
Not all traffic is created equal.When a database is overwhelmed, you want the important queries to keep executing, even if that means shedding lower-priority work.This is a much better outcome than the alternative: a total database outage.
