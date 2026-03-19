0xHimxa
I build autonomous on-chain protocols — prediction markets, cross-chain pricing infrastructure, and agent-native DeFi systems that run without human operators.
Currently exploring cross-chain state consistency and MEV-aware pricing mechanisms.
📧 himxa0x@gmail.com · Open to smart contract, protocol, and DeFi infrastructure roles

What I Build
Prediction market mechanisms — LMSR pricing on the EVM with WAD-scaled fixed-point arithmetic; exp() and ln() computed off-chain in Chainlink CRE and validated on-chain, replacing a constant-product AMM with a theoretically grounded pricing engine
Cross-chain protocol architecture — hub-spoke CCIP topology with dual-path canonical price sync and a 4-band deviation policy engine (fee surcharges, direction locks, circuit breakers) across Arbitrum and Base
Autonomous on-chain systems — 15+ Chainlink CRE handlers across cron, HTTP, and EVM-log triggers automating the full market lifecycle: AI-powered creation, resolution, dispute adjudication, LP withdrawals
Agent delegation infrastructure — 6-layer defense-in-depth for on-chain AI agent trading without custodial risk; funds never leave the router, agents are scoped executors not custodians

Featured
GeoChain — Autonomous Cross-Chain Prediction Markets
An LMSR prediction market protocol where no human operator is needed. Markets are created by AI, priced by math, resolved autonomously, and kept in sync across chains.

No native EVM opcodes for exp()/ln() — solved with off-chain BigInt Taylor series + Halley's method, on-chain invariant validation
Dual-path price propagation (CCIP + CRE direct writes) with progressive circuit breakers protecting spoke markets from stale prices
Three independently deployed CRE workflows — automation, user ops, and agent trading isolated by key set and failure domain

Solidity Chainlink CRE Chainlink CCIP Foundry TypeScript Firebase

Currently

Building — LMSR prediction markets with autonomous CRE workflows
Exploring — cross-chain state consistency and MEV-aware pricing
Open to — smart contract, protocol, and DeFi infrastructure roles
