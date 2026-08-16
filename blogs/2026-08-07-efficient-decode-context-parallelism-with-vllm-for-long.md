---
title: "Efficient Decode Context Parallelism with vLLM for Long Context Workloads"
url: "https://vllm.ai/blog/2026-08-07-decode-context-parallelism"
date: "2026-08-07"
author: "Seonghee Lee, Sungsoo Ha, Omri Almog (NVIDIA), Lucas Wilkinson (Red Hat AI)"
feed_url: "https://vllm.ai/blog/rss.xml"
---
Decode Context Parallelism (DCP) in vLLM shards KV cache across GPUs by sequence dimension, enabling 3× higher throughput on long-context agentic workloads compared to standard tensor parallelism.
