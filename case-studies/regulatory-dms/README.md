# Case Study: Regulatory Document Management System

> **Domain:** Public Sector / Regulatory Agency  
> **Duration:** 1 session (~4 hours)  
> **AI Model:** Claude (Anthropic)  
> **Date:** 2025-02

---

## Overview

This is the first documented ANSELM case study, notable for being **co-authored with an AI co-pilot** who also contributed meta-reflections on the methodology itself.

## Context

A regulatory agency needed to modernize their electronic document management system (DMS). The input was a formal requirements specification (~300 lines) plus sizing estimates (~1500 function points).

**Constraints:**

- On-premise deployment (security requirements)
- ~200 internal users
- Integration with external oversight bodies
- PostgreSQL database (existing infrastructure)
- High document volumes (~60k incoming, ~120k outgoing annually)

## How ANSELM Was Applied

### Phase 1: Raw Ingestion

Raw requirements document was pasted directly into the AI session with the prompt:

> "Analyze using ANSELM method"

This framing immediately set expectations for knowledge-first approach.

### Phase 2: Iterative Reasoning

Through conversation, we explored:

- Stakeholder mapping (6 groups identified)
- Constraint analysis
- 3 architectural variants (Build vs Buy vs Hybrid)
- Technology comparison (low-code vs open-source stack)
- TCO/ROI analysis over 5 years

### Phase 3: Formalizing

Generated artifacts:

- Context diagrams (Mermaid)
- Component diagrams
- Trade-off matrices
- Decision records

### Phase 4: Coherence

Each new artifact was validated against previous decisions. Contradictions were surfaced and resolved.

## Results

| Metric | Value |
| ------ | ----- |
| Time to first analysis | ~2 hours |
| Architectural variants explored | 3 |
| Diagrams generated | 15+ |
| Documents produced | 4 (~2000 lines) |
| Open questions identified | 12 |

## Key Insights

1. **"ANSELM" as prompt framing** — Simply mentioning the methodology changed the entire session dynamic
2. **Disposable views worked** — Diagrams were regenerated 3x without attachment
3. **AI proposed decision frameworks** — Not just options, but how to decide between them
4. **Meta-reflection added value** — AI's perspective on the process became a case study artifact itself

## Knowledge Cells

This case study produced 5 Knowledge Cells:

| File | Topic | Unique Value |
| ---- | ----- | ------------ |
| [experience-report.md](knowledge-cells/experience-report.md) | Experience Report | Session chronology |
| [value-proposition.md](knowledge-cells/value-proposition.md) | Value Proposition | What ANSELM enables |
| [limitations.md](knowledge-cells/limitations.md) | Limitations | Critical analysis |
| [ai-perspective.md](knowledge-cells/ai-perspective.md) | AI Perspective | Meta-reflection from AI |
| [recommendations.md](knowledge-cells/recommendations.md) | Recommendations | Proposals for ANSELM authors |

## Lessons Learned

### What Worked

- Knowledge-first approach prevented premature commitment
- Three-alternatives pattern expanded solution space
- Session checkpoints preserved progress

### What Could Improve

- No formal checklist for ANSELM phases
- Context window limit approached after 4 hours
- Validation relied on linting, not semantic coherence

---

*Complexity seeking clarity.*
