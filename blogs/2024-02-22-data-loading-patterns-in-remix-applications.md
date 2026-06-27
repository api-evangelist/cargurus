---
title: "Data Loading Patterns in Remix Applications"
url: "https://cargurus.dev/2024/02/22/data-loading-patterns-in-remix-applications/"
date: "2024-02-22"
author: "Maxim Milovanov"
feed_url: "https://cargurus.dev/feed/"
---
This article examines three approaches for handling slow data requests in server-side rendering frameworks like Remix. The first provides loading feedback via the useNavigation hook but requires repetition across pages; the second splits rendering into fast initial content and slower supplementary data fetched client-side via resource routes; the third uses Remix's defer and Await components to stream partial responses. Each pattern trades off server-side rendering completeness, time-to-interactive, and code complexity differently.
