# vLLM (vllm)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
