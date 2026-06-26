# whitelabel-internship

> Train → real work → certify → job offer. A paid internship pipeline that creates real employment opportunities for people with disabilities, scaffolded by the whitelabel.dev assistive-AI stack.

## status

**Claimed 2026-06-26.** Operational scope — not just a placeholder. Program structure captured below.

## the four phases

Each intern moves through these in sequence. Each phase has clear entry/exit criteria so the path is legible to interns, funders, and hiring partners.

### Phase 1 — Train

- **Curriculum tracks** by domain: dev (front-end / back-end), design, ops, support, content, sales/marketing, data
- **Assistive scaffolding** from day one: humanoid robot (where motor-skill constraints apply), AI assist (transcription, summarization, on-the-fly UI adaptation), adaptive surfaces — all via [whitelabel-accessibility](https://github.com/whitelabel-dev/whitelabel-accessibility)
- **Paid stipend during training** (funded via [whitelabel-charity](https://github.com/whitelabel-dev/whitelabel-charity) and government channels — VR, WIOA, Ticket to Work)
- **Entry criteria**: enrolled, basic accessibility profile completed
- **Exit criteria**: track-specific competency benchmarks passed

### Phase 2 — Real Work

- **Assignments inside the whitelabel.dev ecosystem** — interns ship real PRs, design real components, handle real customer tickets. Not busywork.
- **Reseller-agency client work** — through partner agencies, interns work on real client projects with full scaffolding included
- **Mentorship pairing** — every intern paired with an ecosystem engineer/designer/etc. who reviews work and unblocks
- **Track output in [whitelabel-orchestrator](https://github.com/whitelabel-dev/whitelabel-orchestrator)** so contribution is visible + claimable
- **Paid at market rate for the work delivered** (not internship sub-rate). Wage-based, not stipend-based.

### Phase 3 — Certify

- **Platform certifications** — whitelabel.dev-issued credentials per track (Front-end Dev, Customer Support Engineer, Content Producer, etc.)
- **Industry certifications** — sponsored vouchers for AWS / Stripe / HubSpot / equivalents the certification path calls for
- **Portfolio** — interns leave with a public portfolio of shipped work (GitHub contributions, deployed surfaces, customer wins)
- **Verifiable claims** — every certification is signed + verifiable via the platform (no résumé-padding)

### Phase 4 — Place

- **Direct hire into the ecosystem** when fit + open headcount align — the most-likely outcome for top performers
- **Placement into reseller agencies** — agencies in the whitelabel.dev reseller program get first-look at interns. The accessibility scaffolding stays with the worker.
- **Placement into outside companies** — federal contractors needing Section 503 compliance, AbilityOne nonprofits, partner companies
- **Self-employment / starting a small business** — supported with seed grants from [whitelabel-charity](https://github.com/whitelabel-dev/whitelabel-charity), platform access, and continued AI/robot scaffolding
- **Continued scaffolding post-placement** — the assistive AI and adaptive surfaces follow the worker into the job; they're the worker's tools, not the program's

## funding model

The program isn't customer-direct. It's funded by:

| Source | What it pays for | Notes |
|---|---|---|
| **State Vocational Rehabilitation (VR)** | Per-intern training + AT + job-coaching costs | TWC-VRS in Texas first; expand state-by-state |
| **WIOA / state workforce boards** | Training subsidies, work-experience wages | Disability-targeted line items in most states |
| **Ticket to Work (SSA)** | Placement bonuses + retention payments | Become an Employment Network (EN) |
| **Section 503 federal contractors** | Pay for placement of interns into their workforce | Compliance-driven demand |
| **SBIR/STTR (NIDILRR, NSF)** | Platform R&D — assistive AI + humanoid robot integration | Non-dilutive |
| **whitelabel-charity** | Stipends + tuition + assistive-tech grants | 501(c)(3) once established |
| **Reseller agencies** | Pay for interns placed on their client work | Margin shared with intern |

Full breakdown lives in [`whitelabel-accessibility/funding/government-pathways.md`](https://github.com/whitelabel-dev/whitelabel-accessibility).

## related repos

| Repo | How it connects |
|---|---|
| [whitelabel-accessibility](https://github.com/whitelabel-dev/whitelabel-accessibility) | Assistive AI + adaptive surfaces interns use throughout |
| [whitelabel-charity](https://github.com/whitelabel-dev/whitelabel-charity) | Funds stipends + scholarships + start-up grants |
| [whitelabel-principles](https://github.com/whitelabel-dev/whitelabel-principles) | Doctrine — disability-employment non-negotiables apply here |
| [whitelabel-jobs](https://github.com/whitelabel-dev/whitelabel-jobs) | Placement board — Phase 4 destinations land here |
| [whitelabel-leads](https://github.com/whitelabel-dev/whitelabel-leads) | Outreach surface — find candidates + employer partners |
| [whitelabel-orchestrator](https://github.com/whitelabel-dev/whitelabel-orchestrator) | Tracks intern work output |
| [whitelabel-guide](https://github.com/whitelabel-dev/whitelabel-guide) | Adjacent apprentice environment (general learners) — share curriculum + tooling |
| [whitelabel-robotics](https://github.com/whitelabel-dev/whitelabel-robotics) | Future humanoid-robot scaffolding (placeholder) |
| [whitelabel-deep-learning](https://github.com/whitelabel-dev/whitelabel-deep-learning) | CV + STT models powering assistive AI |

## non-negotiables (from the doctrine)

Inherits all 5 non-negotiables from [`whitelabel-principles/doctrines/disability-employment.md`](https://github.com/whitelabel-dev/whitelabel-principles). The two most relevant here:

1. **Paid at market rates for the work**, not stipend-only. Charity funds the platform; interns are workers.
2. **The assist is the worker's tool, not surveillance of them.** Mentorship reviews, not monitoring dashboards.

## what doesn't exist yet

Most of this. Curriculum, partner-agency contracts, intern application flow, certification ceremony, placement process, mentor pool — none built. This README is the program design; the implementation comes next.

When implementation starts, the first concrete asset is a **single pilot cohort** (3-5 interns, 1 track, 1 partner agency) in Texas, funded through TWC-VRS + whitelabel-charity stipends. Document everything; that pilot becomes the SBIR Phase I narrative.
