---
title: "IsoExec: Unified Execution to Eliminate Trainer-Inference Mismatch in SkyRL"
url: "https://vllm.ai/blog/2026-08-21-isoexec"
date: "2026-08-21"
author: "Alexander Jiang and the SkyRL Team"
feed_url: "https://vllm.ai/blog/rss.xml"
---
IsoExec unifies numerical execution across SkyRL's vLLM and Megatron runtimes, reducing the average rollout-versus-training logprob difference below 1e-6 on Qwen3.5-35B-A3B with 25% overhead.
