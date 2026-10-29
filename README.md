# CharityAPI

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

CharityAPI provides a simple REST API for data about US nonprofits and charities sourced directly from IRS filings. Developers can retrieve nonprofit records by EIN, verify whether an organization is a public charity (501c3) with tax-deductible status, and integrate organization name autocomplete to power donation, vetting, and compliance workflows.

**Areas:** 501c3 · Charities · Donations · EIN · IRS · Non-Profit · Tax Compliance · Verification

## CharityAPI on APIs.io

Everything profiled for CharityAPI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/charityapi/](https://apis.io/providers/charityapi/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [CharityAPI Autocomplete API](https://apis.io/apis/charityapi/charityapi-autocomplete-api/) — Typeahead search across nonprofit organization names
- [CharityAPI Organizations API](https://apis.io/apis/charityapi/charityapi-organizations-api/) — Look up US nonprofit organization records by EIN
- [CharityAPI Public Charity Check API](https://apis.io/apis/charityapi/charityapi-public-charity-check-api/) — Verify whether an EIN is a tax-deductible public charity

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [charityapi](https://apis.io/servers/charityapi/charityapi/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Charityapi Agentic Access](https://apis.io/agentic-access/charityapi/charityapi-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [CharityAPI Organization](https://apis.io/schemas/charityapi/charityapi-organization/)
- [CharityAPI Public Charity Check](https://apis.io/schemas/charityapi/charityapi-public-charity-check/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Charityapi Context](https://apis.io/jsonld/charityapi/charityapi-context/)

#### Collections (4)

Postman and Open Collection request collections.

- [CharityAPI](https://apis.io/collections/charityapi/open-charityapi/)
- [Charity Autocomplete API](https://apis.io/collections/charityapi/open-charityapi-autocomplete-api/)
- [Charity Autocomplete Organizations API](https://apis.io/collections/charityapi/open-charityapi-organizations-api/)
- [Charity Autocomplete Public Charity Check API](https://apis.io/collections/charityapi/open-charityapi-public-charity-check-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [CharityAPI — jsonschema rules](https://apis.io/rules/charityapi/charityapi-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Charityapi Authentication](https://apis.io/security/charityapi/charityapi-authentication/)
- [Charityapi Domain Security](https://apis.io/security/charityapi/charityapi-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Charityapi Plans Pricing](https://apis.io/plans/charityapi/charityapi-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Charityapi Rate Limits](https://apis.io/rate-limits/charityapi/charityapi-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Charityapi Finops](https://apis.io/finops/charityapi/charityapi-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.charityapi.org/)
- [Documentation](https://docs.charityapi.org/)
- [Pricing](https://www.charityapi.org/pricing)
- [Support](https://www.charityapi.org/contact)
- [Blog](https://www.charityapi.org/news)
- [Terms of service](https://www.charityapi.org/terms)
- [Privacy policy](https://www.charityapi.org/privacy)

## API Evangelist rating

**Kin Score 35.5** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 54.8 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 41.7 |
| Access clarity | 21.1 |

**Agent readiness 47.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | na |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/charityapi/](https://apis.io/providers/charityapi/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for CharityAPI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/charityapi/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
