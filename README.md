# Reservoir (reservoir)

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

Reservoir was an NFT marketplace infrastructure and data API provider that aggregated listings, bids, and sales across major NFT marketplaces including OpenSea, Blur, and others. The platform powered buying, selling, and analytics through a unified API, SDK, and UI kit layer spanning 30+ EVM-compatible blockchains. It was operated by Uneven Labs and used by major Web3 products including Coinbase, MetaMask, and Magic Eden. Reservoir raised $14M in Series A funding from Union Square Ventures. The Reservoir NFT API and all associated services were sunset on October 15, 2025.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/reservoir/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reservoir/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=reservoir-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=reservoir-api-evangelist&utm_content=repo)

## Tags

NFT, Blockchain, Marketplace, Ethereum, EVM, Liquidity, Order Book, Web3, DeFi, Trading, Data API

## APIs

### Reservoir NFT API

All-in-one NFT data and trading API enabling developers to get NFT data, create orders, and execute trades across 30+ EVM-compatible blockchains. Aggregated liquidity from major NFT marketplaces including OpenSea and Blur. Key capabilities included:

- **Trading APIs**: Buy/sell tokens, place and cancel bids, create listings, mint NFTs, transfer tokens
- **Data APIs**: Collections, tokens, attributes, order books, sales history, user portfolios
- **Event Streaming**: Real-time ask/bid status changes, floor price changes, activity feeds
- **ReservoirKit**: React UI component library (BuyModal, ListModal, BidModal, SweepModal, MintModal)
- **Reservoir SDK**: TypeScript SDK with buyToken, listToken, placeBid, acceptOffer, cancelOrder methods
- **Supported Chains**: Ethereum, Polygon, Arbitrum, Optimism, Base, Avalanche, BSC, zkSync Era, and 20+ more

Documentation: [https://nft.reservoir.tools/reference/overview](https://nft.reservoir.tools/reference/overview)

GitHub: [https://github.com/reservoirprotocol](https://github.com/reservoirprotocol)

## Plans, Rate Limits & FinOps

- **Plans**: [plans/reservoir-plans-pricing.yml](plans/reservoir-plans-pricing.yml) — Free, Growth, and Enterprise tiers. Free access via Developer Dashboard API key; paid plans for higher throughput.
- **Rate Limits**: [rate-limits/reservoir-rate-limits.yml](rate-limits/reservoir-rate-limits.yml) — Per-key, per-chain limits. Queryable via `/api-keys/{key}/rate-limits`. Chain-specific keys required (one key per EVM chain).
- **FinOps**: [finops/reservoir-finops.yml](finops/reservoir-finops.yml) — FOCUS-aligned cost allocation by chain and endpoint category; optimization via caching and event streaming over polling.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://reservoir.dev/ |
| Documentation | https://nft.reservoir.tools/reference/overview |
| GitHub | https://github.com/reservoirprotocol |
| LinkedIn | https://www.linkedin.com/company/uneven-labs |
| Blog | https://reservoir.dev/blog |
| Pricing | https://reservoir.tools/pricing |
| StatusPage | https://status.reservoir.tools/ |
| X | https://x.com/reservoir0x |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
