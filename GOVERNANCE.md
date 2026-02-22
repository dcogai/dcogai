# Governance Disclosure (DCogAI)

## Overview
DCogAI adopts a governance structure designed to reduce single-point control risk and provide a public transparency window for sensitive actions.

## Governance Flow
**Multisig approval → Timelock delay → On-chain execution**

## Key Addresses (BNB Smart Chain, Chain ID: 56)
- **Token (Proxy):** 0xA413b1cf3Db08a17E1391866538F8014630420aF
- **Multisig (Gnosis Safe, 3/5):** 0x062D424FfDE386c4F7F86D27136425fA1498478f
- **TimelockController (48h delay):** 0x5fF69e87Cdb83530dD26b9F7c6fF3B348375F105

## Security Controls
- Proxy upgrade authority is controlled via Timelock.
- Core administrative privileges are transferred to Timelock.
- No single externally owned account can execute critical actions unilaterally.

## Verification
All addresses and governance-related transactions are publicly verifiable on BscScan.

## Disclaimer
This document is provided for transparency purposes and does not constitute financial, legal, or investment advice.
