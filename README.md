# mstrmnd.md

Canonical brain for every MSTRMND agent—Claude Code, Codex, Cursor, OpenAI Agents, Gemini CLI, voice agents, and future systems. Each agent should load the same knowledge base so it shares a consistent understanding of the company, philosophy, commercial model, architecture, governance, and engineering practices.

## Canonical Positioning

> MSTRMND installs the intelligence layer between a company's vision and its daily execution.

MSTRMND is the operational intelligence and orchestration layer that connects organizational knowledge, people, software, AI models, tools, workflows, policies, and company-specific skills into one coherent, continuously improving operating environment.

## Repository Structure

### Company Doctrine

- `company/philosophy.md` — purpose, beliefs, human-machine relationship, and long-term view
- `company/canon.md` — non-negotiable rules for MSTRMND systems and agents
- `strategy/positioning.md` — category, principles, messaging, and terminology

### Commercial System

- `commercial/offers-and-pricing.md` — offer ladder, implementation model, pricing, entry offers, and ideal customers
- `commercial/sales-playbook.md` — discovery, qualification, sales narrative, objection handling, metrics, and go-to-market

### Platform Architecture

- `platform/intelligence-architecture.md` — vision-to-execution architecture and core operating loop
- `platform/security-governance.md` — identity, permissions, approvals, data governance, and incident response
- `platform/evaluation-observability.md` — scorecards, tracing, testing, economics, and change management

### Reusable Operating Components

- `agents/agent-specification.md` — standard contract for governed agents
- `skills/skill-standard.md` — standard for reusable, tested capabilities
- `connectors/connector-standard.md` — standard for interoperable company and third-party integrations

### Brand, Research, and Roadmap

- `design/brand-system.md` — voice, terminology, visual direction, and experience principles
- `research/research-standard.md` — evidence, sourcing, market intelligence, and benchmarking
- `roadmap/company-operating-system.md` — path from canonical documentation to executable operating system

## Loading Order for Agents

Agents should load only the context relevant to their task, but use this priority order when instructions conflict:

1. current authorized user or operator instruction;
2. applicable company policy and `company/canon.md`;
3. agent specification and permissions;
4. approved workflow and skill documentation;
5. connector-specific rules;
6. platform and domain guidance;
7. examples and historical material.

At minimum, a general MSTRMND agent should load:

1. `company/canon.md`
2. `strategy/positioning.md`
3. the applicable agent specification
4. the relevant skills, connectors, and domain documentation

## Usage

Agents and operators should treat this repository as authoritative context for:

- company positioning and strategy;
- website and marketing copy;
- discovery calls, proposals, and scopes of work;
- product and systems architecture;
- client recommendations and implementation;
- agent, skill, connector, and workflow design;
- security, evaluation, and observability;
- internal planning, research, and roadmap decisions.

## Access from `mstrmnd-core`

Keep this repository private and grant `mstrmnd-core` read-only access rather than making the repository public or moving it into the application repository.

Preferred approach:

1. provision a dedicated service identity for `mstrmnd-core`;
2. grant read-only access to this repository only;
3. fetch versioned files or repository snapshots over the GitHub API or authenticated git;
4. pin the consumed revision so runtime behavior is tied to a known knowledge version;
5. rotate and revoke credentials independently of application deploys.

Access guidance:

- use least-privilege credentials scoped to repository contents read access;
- prefer a GitHub App for long-term production access;
- use a fine-grained read-only token only as a fast bootstrap path;
- avoid broad personal access tokens and shared operator credentials;
- do not expose credentials in prompts, logs, generated content, or client-visible traces.

Repository boundary guidance:

- keep `mstrmnd.md` separate when it is the canonical cross-agent source of truth;
- move material into `mstrmnd-core` only when it becomes application-specific implementation detail rather than shared doctrine;
- do not require public access just to make the knowledge consumable by agents or runtimes.

## Core Operating Principle

MSTRMND does not add isolated AI tools for their own sake. It creates governed, interoperable systems that align business intent with execution and improve through measurable feedback.

## Repository Governance

`main` represents reviewed company doctrine. Material changes should arrive through pull requests with clear rationale. Outdated or conflicting guidance should be revised or retired rather than silently ignored.
