---
title: "Faster PlanetScale Postgres connections with Cloudflare Hyperdrive"
url: "https://planetscale.com/blog/cloudflare-hyperdrive-real-time"
date: "2026-02-19"
author: "Simeon Griggs"
feed_url: "https://planetscale.com/blog/rss.xml"
---
Cloudflare recently launched Hyperdrive, which provides efficient pooling and fast queries for any MySQL or Postgres database—making optimizing how your application connects to your database incredibly easy. Once you're operating inside the Cloudflare network you get access to the full suite of features, including WebSockets—which we can use to build a real-time experience. In this post, I'm going to outline the decisions made along the way while building a real-time application backed by PlanetScale Postgres Metal.
