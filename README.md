# Tidio (tidio)

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
