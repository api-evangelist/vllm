# vLLM (vllm)

vLLM is a high-throughput, memory-efficient open-source inference and serving engine for LLMs. It provides an OpenAI-compatible REST server (vllm serve) plus a Python API. vLLM is Apache 2.0 and run on your own GPU infrastructure; there is no hosted vLLM SaaS from the project itself.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vllm/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vllm/refs/heads/main/apis.yml)

## Tags

- LLM
- Inference
- Open Source
- GPU
- OpenAI Compatible
- Self-Hosted

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### vLLM OpenAI-Compatible Server

OpenAI-compatible REST API exposed by `vllm serve`. Endpoints include /v1/chat/completions, /v1/completions, /v1/embeddings, /v1/score, /v1/audio/transcriptions, /v1/audio/translations, /v1/realtime (WebSocket), /tokenize, /detokenize, and /generative_scoring. Authentication via the --api-key flag set on server start; clients can use the official OpenAI Python library unmodified, with vLLM-specific extensions passed via extra_body.

- **Human URL:** [https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html](https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html)
- **Base URL:** `http://localhost:8000/v1`

#### Tags

- Chat
- Completions
- Embeddings
- Audio
- Score
- OpenAI-Compatible

#### Properties

- [Documentation](https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html)
- [Git Hub](https://github.com/vllm-project/vllm)
- [Open A I Compat](https://platform.openai.com/docs/api-reference)
- [Postman Collection](collections/vllm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vllm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vllm-project)
- [Website](https://docs.vllm.ai/)
- [Developer Portal](https://docs.vllm.ai/)
- [Open Source](https://github.com/vllm-project/vllm)
- [Plans](plans/vllm-plans-pricing.yml)
- [Rate Limits](rate-limits/vllm-rate-limits.yml)
- [Fin Ops](finops/vllm-finops.yml)
- [L L Ms Txt](https://vllm.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
