# AirDNA (airdna)

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

AirDNA provides short-term rental market data and analytics for Airbnb and Vrbo, tracking over 10 million listings across 120,000+ markets. The AirDNA Enterprise API exposes market metrics, STR listing data, comparable property sets, Rentalizer revenue estimates, and Smart Rates pricing through a Bearer-authenticated REST interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/airdna/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/airdna/refs/heads/main/apis.yml)

## Tags

- Short-Term Rental
- Vacation Rental
- Market Data
- Real Estate
- Analytics

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### AirDNA Market Search

Search for markets and submarkets by search term or coordinates, explore markets within a country, and resolve whether AirDNA has a location mapped and under what market type.

- **Human URL:** [https://docs.airdna.co/](https://docs.airdna.co/)
- **Base URL:** `https://api.airdna.co/api/enterprise/v2`

#### Tags

- Market Search
- Markets
- Submarkets

#### Properties

- [Documentation](https://docs.airdna.co/)
- [API Reference](https://airdna.redoc.ly/)
- [OpenAPI](openapi/airdna-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airdna.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airdna.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AirDNA Market Stats

Time-series market and submarket metrics including occupancy, revenue, average daily rate (ADR), RevPAR, booking lead time, length of stay, active listings, and future daily pricing across 12-60 month windows.

- **Human URL:** [https://docs.airdna.co/](https://docs.airdna.co/)
- **Base URL:** `https://api.airdna.co/api/enterprise/v2`

#### Tags

- Market Metrics
- Occupancy
- Revenue
- ADR
- RevPAR

#### Properties

- [Documentation](https://docs.airdna.co/)
- [API Reference](https://airdna.redoc.ly/)
- [OpenAPI](openapi/airdna-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airdna.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airdna.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AirDNA Property/Listing Data

Search and explore individual short-term rental listings by term, coordinates, country, market, submarket, or radius; fetch listing details and historical performance metrics for one or many listings.

- **Human URL:** [https://docs.airdna.co/](https://docs.airdna.co/)
- **Base URL:** `https://api.airdna.co/api/enterprise/v2`

#### Tags

- Listings
- STR Data
- Properties

#### Properties

- [Documentation](https://docs.airdna.co/)
- [API Reference](https://airdna.redoc.ly/)
- [OpenAPI](openapi/airdna-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airdna.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airdna.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AirDNA Rentalizer Estimates

Rentalizer revenue estimates that project how an address could perform as a short-term rental over the next twelve months, with detailed single-address, bulk multi-address, and summarized lead-gen estimate endpoints.

- **Human URL:** [https://docs.airdna.co/](https://docs.airdna.co/)
- **Base URL:** `https://api.airdna.co/api/enterprise/v2`

#### Tags

- Rentalizer
- Revenue Estimates
- Valuations

#### Properties

- [Documentation](https://docs.airdna.co/)
- [API Reference](https://airdna.redoc.ly/)
- [OpenAPI](openapi/airdna-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airdna.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airdna.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AirDNA Comps

Fetch the most comparable rental properties for a given listing, returning listing details for a competitive comp set used to benchmark short-term rental performance.

- **Human URL:** [https://docs.airdna.co/](https://docs.airdna.co/)
- **Base URL:** `https://api.airdna.co/api/enterprise/v2`

#### Tags

- Comps
- Comparable Listings
- Comp Set

#### Properties

- [Documentation](https://docs.airdna.co/)
- [API Reference](https://airdna.redoc.ly/)
- [OpenAPI](openapi/airdna-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/airdna.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/airdna.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/airdna)
- [Website](https://www.airdna.co)
- [Documentation](https://docs.airdna.co/)
- [Plans](plans/airdna-plans-pricing.yml)
- [Rate Limits](rate-limits/airdna-rate-limits.yml)
- [Fin Ops](finops/airdna-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
