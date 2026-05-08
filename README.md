# vLLM (vllm)

vLLM is a high-throughput, memory-efficient open-source inference and serving engine for LLMs. It provides an OpenAI-compatible REST server (vllm serve) plus a Python API. vLLM is Apache 2.0 and run on your own GPU infrastructure; there is no hosted vLLM SaaS from the project itself.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vllm/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- LLM, Inference, Open Source, GPU, OpenAI Compatible, Self-Hosted

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### vLLM OpenAI-Compatible Server
OpenAI-compatible REST API exposed by `vllm serve`. Endpoints include /v1/chat/completions, /v1/completions, /v1/embeddings, /v1/score, /v1/audio/transcriptions, /v1/audio/translations, /v1/realtime (WebSocket), /tokenize, /detokenize, and /generative_scoring. Authentication via the --api-key flag set on server start; clients can use the official OpenAI Python library unmodified, with vLLM-specific extensions passed via extra_body.
- **Base URL:** `http://localhost:8000/v1`
- **Docs:** https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html

## Common Properties
- [Website](https://docs.vllm.ai/)
- [Developer Portal](https://docs.vllm.ai/)
- [OpenSource](https://github.com/vllm-project/vllm)
- [Plans](plans/vllm-plans-pricing.yml) — reconciled (free Apache 2.0 OSS)
- [RateLimits](rate-limits/vllm-rate-limits.yml) — reconciled (no built-in cap; GPU-bound throughput)
- [FinOps](finops/vllm-finops.yml) — reconciled (FOCUS-aligned)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
