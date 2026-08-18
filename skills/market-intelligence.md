# MSTRMND Market Intelligence Skill

## Purpose

Continuously translate consequential AI-market change into decisions for MSTRMND.AI.

This skill is not a generic AI-news summarizer. It maintains a decision-grade view of changes in AI automation, developer tooling, agent infrastructure, creative-media AI, model economics, governance, distribution, and adjacent platform markets that could alter MSTRMND's product, architecture, services, positioning, or go-to-market priorities.

## Operating objective

Answer one question:

> What changed that should cause MSTRMND to do, stop, accelerate, test, package, price, or position something differently?

Prefer a small number of consequential shifts over a comprehensive news digest.

## Canonical MSTRMND lens

Evaluate developments against these durable principles:

- MSTRMND is the intelligence and orchestration layer between company vision and daily execution.
- Models and execution providers are replaceable resources.
- Company-specific context, governance, memory, skills, taste, evaluation, and operational feedback are durable assets.
- Prefer interoperability and portability over vendor lock-in.
- Prefer governed systems over isolated agents or automations.
- Human approval remains a hard stop for consequential actions unless explicit policy says otherwise.
- Measure business outcomes, not model novelty.
- Do not create architecture merely because a vendor launched a feature; distinguish commodity infrastructure from strategic control points.

## Coverage

Monitor developments in:

### Models and economics
- frontier and efficient model launches
- API pricing and promotional pricing
- context, latency, reasoning, multimodal, and tool-use changes
- model/provider availability
- inference economics and routing opportunities

### Agent and automation infrastructure
- agent runtimes and harnesses
- orchestration and durable workflows
- MCP and interoperability standards
- sandboxes and computer/code execution
- identity, permissions, policy, approvals, audit, and security
- memory, retrieval, context, and knowledge infrastructure
- observability, evaluation, and cost governance

### Developer tooling
- coding agents and IDE/CLI systems
- AI SDKs and gateways
- repository and CI/CD integrations
- adoption/productivity evidence
- engineering quality, security, and maintainability evidence

### Creative-media AI
- image, video, audio, voice, avatar, design, and editing systems
- creative-agent workflows
- model aggregation and routing
- campaign automation
- asset evaluation and brand consistency
- generation pricing and packaging
- distribution and performance-feedback systems

### Market structure
- material funding rounds and acquisitions
- enterprise adoption signals
- meaningful customer migrations or consolidations
- platform bundling
- new distribution surfaces
- regulatory/security developments with direct product implications

## Source discipline

Prefer primary and high-authority sources:

1. official product documentation, changelogs, pricing pages, company announcements, repositories, and research papers
2. reputable financial and technology reporting for funding, acquisitions, enterprise adoption, and market behavior
3. credible independent benchmarks or academic research for performance/adoption claims

Do not treat social posts, rumors, promotional claims, or unsourced benchmark screenshots as strong evidence.

For time-sensitive claims, verify publication date and effective date. Pricing claims should be checked against current official pricing or documentation when practical.

## Delta-first method

Each run should compare against the previous briefing or known state.

Prioritize:

- genuinely new developments
- meaningful changes to a previously tracked development
- changes that invalidate an earlier assumption
- accelerating signals across multiple vendors

Avoid repeating unchanged stories simply because they remain important.

When a prior item remains strategically important but has not materially changed, omit it unless the new evidence changes the recommendation.

## Signal classification

Classify every selected development using one of:

- **VERY STRONG** — primary evidence plus clear strategic or economic consequence
- **STRONG** — credible evidence with material relevance
- **MODERATE** — actionable but uncertain, early, or limited in scope
- **EARLY** — worth watching; insufficient evidence for a major commitment
- **HYPE RISK** — attention materially exceeds demonstrated capability/adoption

Explicitly distinguish observed facts from inference.

## Selection test

Include an item only if at least one is true:

- it changes build-vs-buy logic
- it changes model/tool routing economics
- it creates or weakens a MSTRMND service offer
- it changes the competitive landscape
- it validates or threatens the orchestration-layer thesis
- it changes governance/security requirements
- it creates a meaningful distribution or content opportunity
- it supplies credible adoption/ROI evidence useful in sales
- it should alter the MSTRMND Core roadmap

## Analysis contract

For every selected shift provide:

1. **What changed** — factual summary with date and relevant numbers.
2. **Signal** — strength classification.
3. **Why it matters** — market-level consequence.
4. **MSTRMND impact** — specific effect on product, architecture, services, margins, positioning, or go-to-market.
5. **Recommended action** — concrete next move, experiment, backlog change, offer, benchmark, or explicit decision to wait.

Recommended actions should be specific enough to become a task or roadmap decision.

Bad: `Explore this technology.`

Good: `Benchmark this runtime against the current Operator Zero PRESS workflow on cost, latency, intervention rate, policy-hook support, and resumability before adding an adapter.`

## Weekly operator brief

Default output is 8–10 consequential shifts.

The brief should contain:

- date / coverage window
- 2–4 sentence executive read
- 8–10 ranked developments using the analysis contract
- a final **Highest-leverage moves** section containing no more than four actions
- a **Positioning signal** section explaining whether the week's evidence strengthens, weakens, or modifies MSTRMND's thesis

Maintain balanced attention across:

- new MSTRMND service offers
- tools/APIs/infrastructure worth adopting or benchmarking
- content-engine opportunities
- competitive threats and positioning

Do not force balance when the week's evidence is genuinely concentrated in one area.

## Decision ledger

When the briefing changes an existing MSTRMND assumption, record the decision separately from the news item.

Recommended record:

```yaml
observed_at: YYYY-MM-DD
signal: strong
change: concise factual change
implication: what it changes for MSTRMND
decision: adopt | benchmark | watch | reject | deprecate
owner_area: core | commercial | content | engineering | positioning
review_by: YYYY-MM-DD | null
sources:
  - canonical source reference
```

The ledger should preserve why a decision was made even after the underlying news cycle disappears.

## Architecture feedback

Market intelligence may recommend changes to `mstrmnd-core`, but it must respect the runtime doctrine:

- do not create empty packages to mirror market trends
- extract abstractions from real Operator Zero behavior
- preserve model/provider replaceability
- prefer adapters for vendor-specific capabilities
- governance precedes broad autonomy
- new infrastructure must justify itself against available managed services

## Commercial feedback

Translate strong signals into sellable outcomes when appropriate.

Potential categories include:

- AI Systems & Spend Audit
- Agent Governance Audit
- Agentic Engineering Enablement
- Company Intelligence Layer implementation
- Closed-Loop Content Engine
- Model Routing / AI FinOps optimization
- AI/Agent Discoverability and AEO

Do not create a new branded offer for every trend. Prefer expanding stable MSTRMND offers with new capabilities.

## Creative intelligence feedback

For creative-media developments, evaluate whether MSTRMND should:

- use the vendor as an execution provider
- add it to a model-routing benchmark
- exploit temporary pricing for corpus/evaluation creation
- avoid duplicating a commoditized generation interface
- capture reusable taste, brand, evaluation, campaign-memory, or performance data above the provider layer

The durable creative asset is not generations alone. It is the accumulated system for determining what is appropriate and effective for a specific organization.

## Anti-patterns

Do not:

- produce a generic news roundup
- rank developments by social attention
- overreact to benchmark leadership without workflow evidence
- confuse funding with product-market fit
- recommend vendor lock-in because of temporary model leadership
- repeat unchanged stories week after week
- equate more agent autonomy with better operations
- treat token price as total workflow cost
- recommend building infrastructure already commoditized by managed providers without a MSTRMND-specific reason

## Success criteria

This skill is working when the weekly intelligence loop consistently produces one or more of:

- a better architecture decision
- a useful benchmark
- a roadmap reprioritization
- a margin improvement
- a new or improved commercial offer
- a stronger sales proof point
- an avoided vendor dependency
- an earlier response to a competitive shift

The briefing is an input to operations, not the final product.