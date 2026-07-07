# RTS Ecosystem Status

Status: PUBLIC INDEX / ECOSYSTEM MAP / MAINTAINED SUMMARY

Last reviewed: 2026-07-08

This document is a public-safe summary of the RTS ecosystem.

It is an index, not an operations log.

It should help first-time visitors, collaborators, reviewers, and future AI assistants understand which repositories are active, which are reference material, which are component shelves, and which are intentionally inactive.

## Public Rule

Keep this file concise and public-safe.

Do not place private context, customer information, secrets, internal incident logs, or raw operating notes here.

Detailed protocol material should live in the canonical RTS repository.

Product-specific work should stay in the relevant product repository.

## Canonical / Core

| Repository | Role | Current Use |
|---|---|---|
| `RTS` | Canonical protocol and ecosystem map | Source of truth for RTS concepts, ecosystem relations, and reconstructability rules |
| `RTS-Minimal-Runtime` | Minimal reference runtime | Smallest inspectable proof of the RTS-style execution flow |

## Active Work

| Repository | Role | Current Use |
|---|---|---|
| `RTS-AGE` | Agentic gateway / implementation lab | Prepare implementation artifacts and test agentic execution ideas under review boundaries |
| `RTS-minicompany` | Solo business operation MVP | Support sales, proposal, delivery preparation, risk checks, and operational records |
| `rts01-offer` | Public offer / sales surface | Present the AI development reset and project audit offer |
| `seminar-compass` | Product candidate | Learning reconstruction and seminar understanding workflow |

## Component Shelves

| Repository | Role | Current Use |
|---|---|---|
| `RTS-Skills-` | Skills shelf | Reusable job-shaped skill definitions and skill inventory |
| `RTS-MCP-Packs` | Connector pack shelf | Declarative MCP connector pack definitions and permission review |
| `RTS-Hermes-Drive` | Drive / orchestration shelf | Thin drive declarations connecting triggers, skills, packs, and RTS outputs |
| `RTS-Design-Research` | Design research shelf | UI references, design observations, and implementation-neutral decision material |
| `rts-dev-protocol` | Development protocol shelf | AI implementation contracts, PR hygiene, review checklists, and rescue procedures |

## Public Surface

| Repository | Role | Current Use |
|---|---|---|
| `nobutakayamauchi` | GitHub profile surface | Public identity and entry point for the RTS ecosystem |

## Frozen / Review-Only Shelves

| Repository | Status | Current Use |
|---|---|---|
| `RTS-Talent-Registry` | FREEZE / GOVERNANCE-REGISTRY / REVIEW BEFORE USE | External AI talent governance registry concept; not active recruiting or runtime infrastructure |
| `RTS-Signal-Feeds` | FREEZE / SIGNAL-SKELETON / REVIEW BEFORE USE | Non-executable signal intelligence skeleton; not live collection, publishing, or routing infrastructure |
| `rts-video-flow` | FREEZE / VIDEO-WORKFLOW / REVIEW BEFORE USE | Local video workflow prototype; not a production publishing pipeline |
| `AIX` | FREEZE / TRADING-LAB / DO NOT ACTIVATE | Private research scaffold; not production trading infrastructure or advice |

## Inactive / Minimal Repositories

| Repository | Status | Current Use |
|---|---|---|
| `codex-connector-test` | ARCHIVE / TEST-FIXTURE / DELETE CANDIDATE | Public connector-test sandbox; not production RTS work |
| `rts-lite` | INACTIVE / EMPTY PLACEHOLDER / REVIEW ONLY | Empty placeholder; active minimal RTS work belongs in `RTS-Minimal-Runtime` |

Private or one-off test repositories may be handled separately and do not need to be listed here unless they become public-facing or ecosystem-relevant.

## Recent Rescue Pass

The current rescue pass added or confirmed lightweight repository guardrails across the ecosystem:

- `STATUS.md` for repository role and current decision
- `NEXT.md` for the next smallest safe action
- `AGENTS.md` for AI editing boundaries where useful
- ecosystem and project registry material in the canonical RTS repository
- public profile maintenance guardrails in this repository
- explicit freeze or inactive labels for repositories that should not be treated as active work

The rescue pass did not aim to make every repository active.

Its purpose was to make each repository understandable, bounded, and easier to safely resume or ignore.

## Working Rule

Do not treat every repository as active work.

Use this operating split:

| Class | Meaning |
|---|---|
| Canonical | Defines source-of-truth concepts or reference behavior |
| Active Work | May be worked on directly for product, business, or implementation progress |
| Component Shelf | Holds reusable parts, references, manifests, or procedures |
| Public Surface | Explains the ecosystem to outside readers |
| Frozen / Review-Only | Preserved but not active unless a new decision revives it |
| Inactive / Minimal | Kept only as a placeholder or historical reference unless needed later |

## Current Focus

The practical focus should stay narrow:

1. sell or validate a concrete offer
2. process work through `RTS-minicompany`
3. use `RTS-AGE` only when implementation assistance is needed
4. keep component shelves available but inactive unless pulled into a concrete task
5. leave frozen and inactive repositories alone unless a specific review task exists

## Update Policy

Update this file when:

- a repository changes class
- a repository becomes active or frozen
- a public-facing repository is added or removed
- the canonical RTS ecosystem map changes materially
- a rescue pass completes and needs a public-safe summary

Do not update this file for every commit, experiment, or internal operating note.
