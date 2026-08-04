# Leta

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
