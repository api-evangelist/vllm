---
title: "Large-Scale Sharded Weight Transfer with Ray Direct Transport (RDT) in vLLM"
url: "https://vllm.ai/blog/2026-08-22-rdt-weight-transfer"
date: "2026-08-22"
author: "Aaron Hao, Sumanth Hegde, Gal Meirom, Istvan Haller, Kourosh Hakhamaneshi, Gavin Parnaby, Moein Khazraee, Omri Kahalon"
feed_url: "https://vllm.ai/blog/rss.xml"
---
We implement a native sharded weight transfer engine in vLLM utilizing Ray Direct Transport (RDT), achieving weight transfer for the Kimi K2 model in BF16 on 48 8xH100 nodes in 7.53s
