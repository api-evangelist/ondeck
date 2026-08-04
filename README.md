# OnDeck

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

OnDeck is a small business lending platform that provides partner APIs for submitting loan applications, checking business health scores via the OnDeck Score, managing loan products including term loans and lines of credit, and processing repayments. The API enables banks, brokers, and online service providers to embed OnDeck lending capabilities directly into their own platforms through credit pre-qualification, pre-approval, and full loan application submission workflows. OnDeck is an Enova International brand serving 185,000+ small businesses with $25 billion+ in capital delivered.

- **Website:** https://www.ondeck.com/
- **Partner/API Program:** https://www.ondeck.com/partner
- **Blog:** https://www.ondeck.com/resources
- **LinkedIn:** https://www.linkedin.com/company/ondeck/
- **X (Twitter):** https://twitter.com/OnDeckCapital/

## APIs

### OnDeck Lending API

REST API providing partner access to OnDeck's small business lending platform. Features include:

- Credit pre-qualifications and pre-approvals
- Full loan application submission from partner CRMs and portals
- Business health score retrieval (OnDeck Score)
- Loan product management (term loans and lines of credit)
- Repayment processing

API access requires a partner agreement. Contact partners@ondeck.com or visit the partner portal at https://partners.ondeck.com.

## Loan Products

| Product | Range | Terms | Avg APR |
|---------|-------|-------|---------|
| Business Term Loan | $5K - $400K | Up to 24 months | ~57.90% |
| Business Line of Credit | $6K - $200K | 12, 18, or 24 months | ~56.60% |

## APIs.json

This repository contains an [APIs.json](apis.yml) profile for OnDeck following the [APIs.json 0.19 specification](https://apisjson.org/).
