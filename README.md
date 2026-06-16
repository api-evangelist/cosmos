# Cosmos (cosmos)

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
