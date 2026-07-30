# Leta

Leta is a pan-African logistics technology company founded in 2022 and headquartered in Westlands, Nairobi, Kenya, with operations across Kenya, Nigeria and South Africa. Leta builds an AI-driven delivery management platform — route optimization, automated dispatch and broadcast, live GPS track-and-trace, payment on delivery, fleet management, and delivery analytics — delivered as logistics SaaS plus on-demand and dedicated rider services, including an M-PESA business mini-app.

- Website: https://leta.ai/
- Blog: https://leta.ai/blog/
- Login: https://cloud.leta.ai/auth/login

Backed by: speedinvest

## API surface

As of 2026-07-19, Leta publishes **no public developer portal, API documentation, or OpenAPI**. A live API does exist: `api.leta.ai` runs Django REST Framework, and `/docs/`, `/redoc/`, `/swagger/` and `/api/v1/` all return `401 Authentication credentials were not provided.` The API is customer/partner-gated. Marketing copy refers generically to integrations with "common POS, ERP, and e-commerce platforms" without naming them or linking documentation.

No first-party SDKs were found on npm, PyPI, or a confirmable GitHub organization. No `/.well-known/` documents, status page, changelog, pricing page, or security/trust page are published.

## Artifacts

- `llms/leta-llms.txt` — real `llms.txt` published at https://leta.ai/llms.txt (Rank Math SEO), saved verbatim.
- `well-known/leta-well-known.yml` — probe index for both hosts (all 404; recorded as an honest negative).
- `security/leta-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC for leta.ai, api.leta.ai, cloud.leta.ai.
