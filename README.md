# Cosmos (cosmos)

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

Cosmos is an interoperable blockchain ecosystem providing a modular framework (Cosmos SDK) for building sovereign, high-performance application-specific blockchains. The Cosmos SDK exposes LCD (Light Client Daemon) REST APIs on port 1317, generated automatically via gRPC-gateway from Protobuf definitions. These endpoints cover accounts, balances, transactions, governance proposals, staking delegations, IBC transfers, minting, distribution, and ABCI app data. The Cosmos Hub (cosmoshub-4) is the flagship chain; the same API surface is shared by 150+ chains in the ecosystem.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cosmos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cosmos/refs/heads/main/apis.yml)

## Tags

- Blockchain
- Cosmos
- IBC
- Staking
- Governance
- DeFi
- Web3

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Cosmos Auth API

Query authentication-related data for accounts on a Cosmos SDK chain, including account information, parameters, and address lookups.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/auth](https://docs.cosmos.network/sdk/latest/modules/auth)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Auth
- Accounts
- Authentication

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/auth)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Bank API

Query account balances, total coin supply, denomination metadata, and denom ownership across a Cosmos SDK chain. Supports both individual balance lookups and aggregate supply queries.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/bank](https://docs.cosmos.network/sdk/latest/modules/bank)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Bank
- Balances
- Token Supply
- Denominations

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/bank)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Staking API

Query proof-of-stake data including validators, delegations, unbonding delegations, redelegations, staking parameters, and pool information. Supports querying by delegator address, validator address, and more.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/staking](https://docs.cosmos.network/sdk/latest/modules/staking)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Staking
- Validators
- Delegations
- Proof of Stake

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/staking)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Governance API

Query on-chain governance data including proposals, votes, deposits, and governance parameters. Supports filtering proposals by status and querying individual voter and depositor records.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/gov](https://docs.cosmos.network/sdk/latest/modules/gov)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Governance
- Proposals
- Voting
- Deposits

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/gov)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Distribution API

Query staking reward distribution data including delegator rewards, validator commission, community pool balances, and distribution parameters.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/distribution](https://docs.cosmos.network/sdk/latest/modules/distribution)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Distribution
- Rewards
- Commission
- Community Pool

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/distribution)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Mint API

Query the minting module for inflation parameters, current inflation rate, annual provisions, and minting module parameters for a Cosmos SDK chain.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/mint](https://docs.cosmos.network/sdk/latest/modules/mint)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Mint
- Inflation
- Token Economics

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/mint)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Slashing API

Query validator slashing data including signing information, slashing parameters, and signing info for all validators. Used for monitoring validator uptime and penalty state.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/modules/slashing](https://docs.cosmos.network/sdk/latest/modules/slashing)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Slashing
- Validators
- Signing Info
- Penalties

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/modules/slashing)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos IBC API

Query Inter-Blockchain Communication (IBC) data including channels, clients, connections, and packet commitments. Enables cross-chain transfer queries and IBC state inspection across all 150+ chains in the Cosmos ecosystem.

- **Human URL:** [https://ibc.cosmos.network/v10/](https://ibc.cosmos.network/v10/)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- IBC
- Inter-Blockchain Communication
- Channels
- Clients
- Connections

#### Properties

- [Documentation](https://ibc.cosmos.network/v10/)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos Transactions API

Query and broadcast transactions on a Cosmos SDK chain. Supports fetching transaction details by hash, searching transactions by event filters, simulating transaction gas, and broadcasting signed transactions.

- **Human URL:** [https://docs.cosmos.network/sdk/latest/learn/advanced/grpc_rest](https://docs.cosmos.network/sdk/latest/learn/advanced/grpc_rest)
- **Base URL:** `https://lcd.cosmos.network`

#### Tags

- Transactions
- Broadcast
- Gas Simulation
- Transaction Search

#### Properties

- [Documentation](https://docs.cosmos.network/sdk/latest/learn/advanced/grpc_rest)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cosmos CometBFT RPC API

Query CometBFT (formerly Tendermint) consensus engine data including block information, validator sets, consensus state, network status, and ABCI application data. Exposed on port 26657 independent of the Cosmos SDK LCD.

- **Human URL:** [https://docs.cosmos.network/cometbft/latest/docs/README](https://docs.cosmos.network/cometbft/latest/docs/README)
- **Base URL:** `https://rpc.cosmos.network`

#### Tags

- CometBFT
- Tendermint
- Consensus
- Blocks
- ABCI

#### Properties

- [Documentation](https://docs.cosmos.network/cometbft/latest/docs/README)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/cosmos)
- [GitHub Repository](https://github.com/cosmos/cosmos-sdk)
- [Documentation](https://docs.cosmos.network)
- [OpenAPI](https://cosmos.github.io/cosmos-sdk/openapi.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger U I](https://localhost:1317/swagger)
- [Forum](https://forum.cosmos.network)
- [Discord](https://discord.gg/interchain)
- [Blog](https://blog.cosmos.network)
- [X (Twitter)](https://x.com/cosmosecosystem)
- [Terms of Service](https://cosmos.network/privacy)
- [Plans](https://raw.githubusercontent.com/api-evangelist/cosmos/refs/heads/main/plans/plans.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/cosmos/refs/heads/main/rate-limits/rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/cosmos/refs/heads/main/finops/finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
