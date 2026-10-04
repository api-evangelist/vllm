---
title: "vime × RL-Kernel × AMD: Bitwise Train–Rollout Consistency on ROCm"
url: "https://vllm.ai/blog/2026-09-14-rl-kernel-v0-1-0-train-rollout-bitwise-consistency"
date: "2026-09-14"
author: "RL-Kernel Team, vime Team, and AMD Team"
feed_url: "https://vllm.ai/blog/rss.xml"
---
vime and RL-Kernel align selected-token logprobs bit for bit across Megatron training and vLLM rollout on AMD Instinct MI300X, with zero mismatches across 200 GRPO steps.
