---
title: "Larger than RAM Vector Indexes for Relational Databases"
url: "https://planetscale.com/blog/larger-than-ram-vector-indexes-for-relational-databases"
date: "2025-10-01"
author: "Vicent Martí"
feed_url: "https://planetscale.com/blog/rss.xml"
---
With the advent of modern embedding models, capable of distilling the key traits of arbitrary data (including text, images and audio) into multi-dimensional vectors, the capability to index these vectors and perform similarity queries on them has become table stakes for all database products. There has been a lot of research on this topic over the past decade, but most of it happens in a vacuum: new data structures and algorithms are designed, tested and benchmarked as standalone implementations, attempting to maximize recall and performance without taking in consideration the requirements for
