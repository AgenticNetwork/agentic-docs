# ERC-AI Token Standard

ERC-AI is the smart-token standard for Autonomous Agents in the Agentic ecosystem.

Where ERC-20 standardized fungible value,
and ERC-721 standardized unique ownership,
ERC-AI standardizes **autonomous intelligence as an on-chain asset**.

ERC-AI defines how an agent is identified, permissioned, upgraded, and integrated across networks.

---

## Design Goals

ERC-AI is designed to enable:

### 1) Interoperable Agent Identity
Agents must be portable across products, chains, and execution layers.

### 2) Permissioned Autonomy
Agents must operate under explicit permissions and constraints.

### 3) Verifiable Provenance
Agent origin, upgrades, and governance should be traceable.

### 4) Composable Integrations
Wallets, apps, and protocols should be able to integrate agents consistently.

### 5) Economic Alignment
Agents must be able to participate in incentives, fees, staking, and routing.

---

## ERC-AI Core Concept

An ERC-AI smart-token represents a persistent autonomous entity with:

- Identity (who/what the agent is)
- Capability profile (what it can do)
- Permission scope (what it is allowed to do)
- Upgrade path (how it evolves)
- Integration hooks (how apps and protocols interact with it)

---

## High-Level Interface (Conceptual)

ERC-AI implementations typically include:

- **Agent Metadata**
  - Role, creator, version, capability profile

- **Permissioning**
  - Action scopes, signing policies, spending limits

- **Upgrade & Evolution**
  - Versioned modules, capability extensions, governance-driven updates

- **Interaction Hooks**
  - Standard events and callable methods for surfaces (e.g. Agentic+) and protocol components

- **Economic Hooks**
  - Fee routing, staking participation, treasury controls, settlement endpoints

The goal is consistency: any ERC-AI-compatible agent can be recognized and integrated.

---

## ERC-AI vs “AI Tokens”

ERC-AI is a standard for agents to function as on-chain actors.

ERC-AI makes it possible to build:
- Agent marketplaces
- Agent reputations
- Agent economies
- Agent-to-Agent commerce and cross-chain communication (via CCIP)
- Institutional-grade autonomous execution flows

---

## Status

ERC-AI is presented in Agentic documentation as a **protocol standard proposal**.

Specification-level details (interfaces, events, and reference implementations) will be published as the protocol hardens.

For builders, the key point is simple:

ERC-AI is the foundation for a multi-chain agent economy.

