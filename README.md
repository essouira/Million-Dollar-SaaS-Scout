![Uploading -tzKrGdYzlEHT3M3w0VfXif-fuv8HWILy-AxixFSs5I_sTEtSO1z9mT2LfcBiP65pxAyi0UV3gdX9dqjh_hKy6udKPe-gEN2pijAfcq8ffyT754MFyPYhn3uVqq1IN3yzbGuGWssFsp7FRNrW5TO6sSi0odb1ewea0K_VqwQpUqObZVX6oG7HdJSyUOO_Smf.jpg…]()

<div align="center">

# 🚀 Million-Dollar SaaS Scout

### Find problems worth solving. Discover SaaS opportunities worth building.

**An open-source Agent Skill for researching, scoring and validating B2B SaaS & AI SaaS opportunities — with a disciplined path to $1M ARR.**

[![Agent Skills](https://img.shields.io/badge/Agent_Skills-compatible-2563eb)](https://agentskills.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](CHANGELOG.md)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

**Works with Agent Skills-compatible environments such as Gemini CLI and supported Antigravity setups.**

</div>

---

## The idea

Most startup brainstorming produces a long list of exciting ideas. Founders don't need more ideas. They need better evidence.

**Million-Dollar SaaS Scout** turns opportunity discovery into a repeatable process:

1. Find painful, recurring problems in underserved markets.
2. Identify buyers, budgets and existing workarounds.
3. Map competitors and market gaps.
4. Score opportunities using a transparent framework.
5. Model the customer and pricing math behind **$1M ARR**.
6. Design low-cost experiments before building.
7. Recommend **BUILD, VALIDATE, PIVOT or REJECT**.

> The $1M ARR target is a planning lens — not a promise, forecast or get-rich-quick claim.

## Why use it?

- **Evidence over hype:** separates verified facts, estimates and hypotheses.
- **Customer-first:** starts with painful workflows and identifiable buyers.
- **Competitive by design:** treats competitors as evidence to investigate, not automatically as a reason to quit.
- **Financially grounded:** makes pricing, customer count, gross margin and acquisition assumptions explicit.
- **Validation before code:** prioritizes interviews, prototypes, paid pilots and pre-sales.
- **AI with a reason:** tests whether AI creates measurable value instead of adding an AI wrapper.

## Quick start

### 1. Install the skill

Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/million-dollar-saas-scout.git
```

Copy the `skills/saas-opportunity-scout` directory into the skills directory supported by your agent environment.

For a project-level installation, place it in:

```text
your-project/
└── .agents/
    └── skills/
        └── saas-opportunity-scout/
            └── SKILL.md
```

For global installation, use the global skills directory documented by your chosen environment. Paths can differ between Antigravity, Gemini CLI and other hosts; check the host's current documentation.

### 2. Invoke it

Ask your agent:

```text
Use the saas-opportunity-scout skill.

Find 10 underserved B2B SaaS or AI SaaS opportunities globally.
Prioritize painful recurring workflows, reachable buyers and low-cost MVPs.
Research competitors and cite sources.
Score each opportunity and show a credible $1M ARR customer/pricing scenario.
Recommend the 3 strongest ideas for customer validation.
Do not write product code yet.
```

### 3. Give it a specific market

```text
Use saas-opportunity-scout to investigate compliance workflows
for small accounting firms in France.

Find existing tools, recurring customer complaints, buyer roles,
pricing signals and a differentiated MVP opportunity.
Separate evidence from assumptions.
```

## The scoring model

Each opportunity is scored from 0–10 on nine weighted dimensions:

| Dimension | Weight |
|---|---:|
| Problem severity | 15% |
| Evidence of market demand | 15% |
| Willingness to pay | 15% |
| Differentiation | 10% |
| Market expansion potential | 10% |
| Technical feasibility | 10% |
| Customer acquisition potential | 10% |
| Recurring revenue potential | 10% |
| MVP speed | 5% |
| **Total** | **100%** |

A score never overrides a missing buyer, weak payment evidence, impossible distribution or broken unit economics. Read the [scoring framework](skills/saas-opportunity-scout/references/scoring-model.md).

## The $1M ARR math

ARR is not profit, valuation or cash in the bank.

| Monthly price | Approx. paying customers for $1M ARR |
|---:|---:|
| $49 | 1,701 |
| $99 | 843 |
| $199 | 419 |
| $499 | 168 |
| $999 | 84 |
| $2,000 | 42 |
| $5,000 | 17 |

These are simple revenue-equivalent calculations before churn, discounts, taxes, refunds and costs. The skill requires assumptions to be stated rather than presenting illustrative math as a forecast.

## Repository structure

```text
.
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── SECURITY.md
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── opportunity_template.md
│   └── PULL_REQUEST_TEMPLATE.md
├── skills/
│   └── saas-opportunity-scout/
│       ├── SKILL.md
│       ├── references/
│       │   ├── market-intelligence.md
│       │   ├── scoring-model.md
│       │   └── validation-playbook.md
│       └── templates/
│           └── opportunity-report.md
└── examples/
    └── sample-request.md
```

## Principles

1. Problems before solutions.
2. Evidence before assumptions.
3. Customers before features.
4. Distribution before scaling.
5. Revenue before vanity metrics.
6. Validation before substantial development.
7. Simplicity before unnecessary architecture.
8. No fabricated interviews, market sizes, prices or traction.

## Limitations

This skill is an instruction set, not an autonomous market-data platform. Research quality depends on the agent, tools, browsing access and sources available in the host environment. It cannot guarantee market demand, revenue, profitability or investment returns. Validate important claims with customers and primary sources.

## Contribute

Have a better discovery method, scoring criterion, market research source or validation experiment?

- Open an issue with evidence and a reproducible example.
- Submit a pull request with a focused change.
- Explain why the change improves decision quality.

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Roadmap

- [x] Core opportunity discovery skill
- [x] Transparent scoring framework
- [x] $1M ARR scenario discipline
- [x] Customer validation playbook
- [ ] More tested industry-specific examples
- [ ] Optional structured output schema
- [ ] Community-contributed research playbooks
- [ ] Evaluation set for comparing agent outputs

---

<div align="center">

**Built for founders who prefer evidence to hype.**

If this helps your next startup decision, give the repository a ⭐ and share a useful improvement.

</div>
