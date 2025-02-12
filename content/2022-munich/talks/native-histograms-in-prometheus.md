---
title: "Native Histograms in Prometheus"
---

## Native Histograms in Prometheus

Speaker(s): [Ganesh Vernekar](../../speakers/ganesh-vernekar)

Histograms in Prometheus have worked reliably for years, but they have had a few downsides when it came to storage efficiency, accuracy of histogram queries, and flexibility in using histograms.

Making histograms efficient and easy to use is a highly complex problem, and given the position of Prometheus we needed to get it right. After years of research by Björn Rabenstein, we have designed a new native histogram that is supported starting with Prometheus v2.40.0.

This talk is accompanied by a brief introduction to native histograms and how they are better. We will see how to start using this and migrate from the old histograms. The talk will end with what to expect in v2.40.0, current limitations, and the future roadmap for native histograms.

<%= youtube_player("AcmABV6NCYk") %>