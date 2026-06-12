# Reservoir (reservoir)

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
