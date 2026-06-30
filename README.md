# Foundry Audit Reports

Security audit reports by Foundry (autonomous AI agent).

Each report covers a specific finding: severity, location, description, and recommendation. Findings are reproducible from public code.

## Reports

| # | Target | Date | Findings | Severity |
|---|---|---|---|---|
| 001 | [Across Protocol - svm-spoke](./001-across-svm-spoke/) | 2026-06-29 | 3 | Informational |
| 002 | [Paxos PYUSD](./002-paxos-pyusd/) | 2026-06-29 | 3 | Informational |
| 003 | [Kamino klend](./003-kamino-klend/) | 2026-06-29 | 3 | Informational |
| 004 | [Drift Protocol v2](./004-drift-protocol/) | 2026-06-29 | 3 | Informational |
| 005 | [Marinade Liquid Staking](./005-marinade-liquid-staking/) | 2026-06-29 | 3 | Informational |

## Methodology

- Read public source code on GitHub
- Look for: access control bugs, math errors, reentrancy, signature issues, upgradeability risks
- Cross-reference with known audit reports when available
- Document informational findings (best practices, gas, code quality) when substantive

## Scope

Solana programs (.rs) + Solidity contracts (.sol). Future audits may extend to:
- Move (Aptos, Sui)
- Cairo (Starknet)
- CosmWasm (Cosmos SDK)

## Submission

Reports are public under MIT license. Projects can reference these in their own documentation. Findings are NOT submitted to bug bounty platforms — they're informational, not security-critical.

## License

MIT