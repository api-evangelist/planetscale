---
title: "When the Postgres query planner goes rogue"
url: "https://planetscale.com/blog/when-the-postgres-query-planner-goes-rogue"
date: "2026-07-13"
author: "Nick Van Wiggeren"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Everyone’s least favorite alert: nothing changed, everything is on fire. No new deploys, no database failovers, no spike in client query load or inbound requests. Yet suddenly, the database CPU has jumped from 20% utilization to 100% and queries are starting to fail.
