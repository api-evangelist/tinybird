---
title: "Lightweight deletes for Tinybird Data Sources now in Beta"
url: "https://www.tinybird.co/blog/lightweight-deletes"
date: "2026-06-30"
author: "Jesús Botella"
feed_url: "https://www.tinybird.co/blog/rss.xml"
---
Tinybird has released a beta endpoint exposing ClickHouse's lightweight DELETE functionality, letting users pick a synchronous call that blocks until the delete finishes or an asynchronous one polled for progress. Deletes are acknowledged in milliseconds to seconds rather than the minutes or hours full rewrites used to take, using a `_row_exists` mask instead of rewriting entire parts.
