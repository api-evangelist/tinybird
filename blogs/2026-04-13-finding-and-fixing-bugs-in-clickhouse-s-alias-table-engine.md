---
title: "Finding and fixing bugs in ClickHouse®'s Alias table engine"
url: "https://www.tinybird.co/blog/fixing-clickhouse-alias-dependency-bug"
date: "Mon, 13 Apr 2026 00:00:00 GMT"
author: "Enric Calabuig"
feed_url: "https://www.tinybird.co/blog/rss.xml"
---
We've been testing ClickHouse®'s experimental Alias table engine. We found bugs in how DDL dependencies are tracked and in how materialized views are triggered and shipped a fix upstream for the former.
