---
title: "vLLM x TileRT: Specialized Decode for Latency-Critical Serving"
url: "https://vllm.ai/blog/2026-07-14-vllm-tilert-pd"
date: "2026-07-14"
author: "TileRT team"
feed_url: "https://vllm.ai/blog/rss.xml"
---
vLLM prefill paired with TileRT decode through vLLM V1's connector interface: a specialized, latency-optimized decode engine that coexists with native vLLM decode behind one shared serving layer, with zero changes to vLLM.
