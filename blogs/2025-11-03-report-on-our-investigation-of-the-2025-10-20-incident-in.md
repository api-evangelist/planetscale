---
title: "Report on our investigation of the 2025-10-20 incident in AWS us-east-1"
url: "https://planetscale.com/blog/aws-us-east-1-incident-2025-10-20"
date: "2025-11-03"
author: "Richard Crowley"
feed_url: "https://planetscale.com/blog/rss.xml"
---
On 2025-10-20, there was an incident that affected PlanetScale, initially caused by DNS misconfiguration in one of PlanetScale’s service providers, followed by several hours of capacity constraints and network instability. The incident occurred in two distinct phases, with the first affecting the PlanetScale control plane and the second affecting some database branches hosted in AWS us-east-1. Our design focus on isolation and static stability put us in a good position to weather this incident with minimal impact.
