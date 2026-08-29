# SW4P Documentation

Public documentation for **SW4P — programmable stablecoin settlement for applications and agents**.

SW4P is explained through the finished settlement outcome:

```text
instruction
→ quote
→ authorization
→ route, fee, and gas policy
→ execution
→ finality
→ proof
→ recovery and reconciliation
```

## Public-documentation rule

Documentation must not publish an SDK package, API key format, endpoint, route, rate limit, chain, asset, fee, speed, or production state unless it is generated from or reconciled against the current implementation authority.

The copy-system review found that the previous repository still contained Mintlify starter material, a Plant Store OpenAPI sample, and unverified SDK/API examples. The canonical-copy branch removes those from public navigation and preserves only the product category, settlement lifecycle, route-state contract, and design-partner integration path until the real developer contract is generated.

## Current scope

- product definition and settlement lifecycle;
- route-state and public-registry requirements;
- integration-readiness and design-partner process;
- failure, recovery, proof, and reconciliation concepts;
- links to RNDRNTWRK and the current reports/disclosures surface.

## Not yet a public contract

Until an implementation-derived reference is admitted, this repository does **not** promise:

- a public API base URL;
- self-service API-key issuance;
- npm, pnpm, Cargo, or other SDK packages;
- endpoint paths or response types;
- free, Pro, or Enterprise rate limits;
- a fixed route or chain matrix;
- a fixed settlement time;
- universal gas sponsorship.

## Development

Install the current Mintlify CLI and preview the documentation from the repository root:

```bash
npm install -g mint
mint dev
```

Before publication, verify:

1. every page is reachable from `docs.json` or deliberately excluded;
2. every current-state statement has an owner and evidence source;
3. no starter, placeholder, or speculative developer contract remains;
4. Mermaid diagrams and Mintlify components render correctly;
5. route and API references are generated from the accepted implementation source.

## Public resources

- [SW4P](https://sw4p.io/)
- [RNDRNTWRK](https://www.rndrntwrk.com/)
- [RNDRNTWRK public corpus](https://www.rndrntwrk.com/corpus)
- [Design partnerships](https://www.rndrntwrk.com/partners)
- [Find reports and disclosures here](https://report.rndrntwrk.com/)
