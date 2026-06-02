---
title: The State of FP8 KV-Cache and Attention Quantization in vLLM
url: https://vllm.ai/blog/2026-04-22-fp8-kvcache
date: '2026-04-22'
author: Jonas Kübler* (AWS), Eldar Kurtić* (Red Hat AI), Lucas Wilkinson (Red Hat
  AI), Matthew Bonanni (Red Hat AI), Michael Goin (Red Hat AI), Alexandre Marques
  (Red Hat AI), Kailash Budhathoki (AWS) (* Equal Contribution)
feed_url: https://vllm.ai/blog/rss.xml
---
Long-context LLM serving is increasingly memory-bound: for standard full-attention decoders, the KV cache often dominates GPU memory at 128k+ contexts, and each decode step must read a large...
