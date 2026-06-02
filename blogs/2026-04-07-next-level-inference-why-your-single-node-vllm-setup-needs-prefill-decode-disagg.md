---
title: 'Next-Level Inference: Why Your Single-Node vLLM Setup Needs Prefill-Decode
  Disaggregation'
url: https://vllm.ai/blog/2026-04-07-moriio-kv-connector
date: '2026-04-07'
author: AMD and Embedded LLM
feed_url: https://vllm.ai/blog/rss.xml
---
TL;DR: Prefill and decode fight over the same GPUs, causing ITL spikes under load. We show how to disaggregate them on a single 8-GPU MI300X node using AMD's MORI-IO connector — achieving 2.5x...
