# Tidio (tidio)

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

Tidio is a customer service platform used by over 300,000 businesses worldwide that combines live chat, AI-powered chatbots (Lyro AI), and email ticketing into a unified support workspace. The platform exposes a REST OpenAPI for managing contacts, conversations, and tickets, a Webhooks system for real-time event notifications, and a JavaScript Widget SDK for front-end customization. Full API access is gated by plan tier, with OpenAPI and Webhooks available on Plus and Premium plans.

APIs.json: https://raw.githubusercontent.com/api-evangelist/tidio/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tidio-api-evangelist&utm_content=repo

## Tags

- live chat
- chatbot
- customer service
- AI
- help desk
- ticketing
- conversations
- contacts
- webhooks
- widget

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Tidio OpenAPI (REST) | REST API for contacts, conversations, tickets, and operators; requires Plus or Premium plan | https://developers.tidio.com/docs/openapi-enable |
| Tidio Webhooks | Real-time event notifications via HTTP POST; Plus and Premium plans only | https://developers.tidio.com/docs/webhooks-introduction |
| Tidio Widget SDK | JavaScript SDK for embedding and customizing the Tidio chat widget | https://developers.tidio.com/docs/widget-introduction |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/tidio-plans-pricing.yml](plans/tidio-plans-pricing.yml) |
| Rate Limits | [rate-limits/tidio-rate-limits.yml](rate-limits/tidio-rate-limits.yml) |
| FinOps | [finops/tidio-finops.yml](finops/tidio-finops.yml) |

**Plan summary:** Free (50 conversations) | Starter $29/mo (100 conversations) | Growth from $59/mo (up to 2,000 conversations) | Plus $749/mo (full API + webhooks) | Premium from $2,999/mo (managed AI, SSO, compliance). Lyro AI and Flows are sold as metered add-ons.

**Rate limits:** 10 req/min (Free Trial, Starter, Growth) | 60 req/min (Plus) | 120 req/min (Premium). Returns HTTP 429 with `x-ratelimit-limit` and `x-ratelimit-remaining` headers.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.tidio.com/ |
| Documentation | https://developers.tidio.com/ |
| Blog | https://www.tidio.com/blog/ |
| Pricing | https://www.tidio.com/pricing/ |
| Status Page | https://status.tidio.com/ |
| LinkedIn | https://www.linkedin.com/company/tidio-ltd |
| X (Twitter) | https://twitter.com/tidiochat |

## Maintainers

- Kin Lane / kin@apievangelist.com
