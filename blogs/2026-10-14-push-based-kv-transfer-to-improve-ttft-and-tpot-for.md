---
title: "Push-Based KV Transfer to Improve TTFT and TPOT for Disaggregated Inference in vLLM"
url: "https://vllm.ai/blog/2026-10-14-nixl-push-connector"
date: "2026-10-14"
author: "Sunita Nadampalli (AWS), Nicolò Lucchesi (Mistral)"
feed_url: "https://vllm.ai/blog/rss.xml"
---
A push-based NIXL connector for vLLM disaggregated serving: the prefill instance writes KV directly into decode memory over RDMA, taking the router relay, decode-side allocation, and transfer setup off the TTFT critical path.
