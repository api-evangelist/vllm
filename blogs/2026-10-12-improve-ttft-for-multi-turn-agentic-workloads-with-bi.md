---
title: "Improve TTFT for Multi-Turn Agentic Workloads with Bi-Directional KV Transfer in vLLM"
url: "https://vllm.ai/blog/2026-10-12-bidirectional-kvxfer-multiturn-agentic-workload"
date: "2026-10-12"
author: "Sunita Nadampalli (AWS)"
feed_url: "https://vllm.ai/blog/rss.xml"
---
Bi-directional KV transfer lets vLLM prefill nodes reuse previously computed KV from decode nodes on later conversation turns, cutting redundant prefill recompute and reducing TTFT by up to 3.3x on long multi-turn prompts.
