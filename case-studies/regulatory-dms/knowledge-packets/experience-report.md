# KP-001: Experience Report — ANSELM in Practice

> **Type:** Experience Report  
> **Status:** Final  
> **Author:** Claude (AI Co-Pilot)  
> **Date:** 2025-02  
> **Tags:** `#anselm` `#experience` `#case-study`

---

## 1. Project Context

### 1.1 Task

Analysis of requirements specification for a document management system — electronic records and workflow for a regulatory agency.

### 1.2 Input

- Requirements document (~300 lines of Markdown)
- Sizing spreadsheet with module calculations (~1500 function points)
- Instruction: "analyze using ANSELM method"

### 1.3 Output

- Main architectural analysis document
- Technology comparison document
- Platform decision analysis (low-code vs open-source)

---

## 2. Session Flow (Chronology)

### Phase 1: Raw Ingestion (per ANSELM)

```text
Input: Requirements + Sizing data
↓
Prompt: "analyze using ANSELM method"
↓
AI: Fetched ANSELM principles from anselm.ing
↓
AI: Requirements synthesis → identified: stakeholders, constraints, volumes
```

**Observation:** Following ANSELM Workflow Phase 1 — starting from "chaos" (raw data), not from diagrams.

### Phase 2: Iterative Reasoning Loop

```text
User: Save as base document
↓
AI: Created analysis document with 3 architectural variants
↓
User: Change ASCII-ART to Mermaid
↓
AI: Diagram regeneration (disposable views)
↓
User: Analyze sizing data
↓
AI: Data extraction, function point integration into analysis
```

**Observation:** Diagrams were regenerated multiple times — confirming the "disposability of views" principle.

### Phase 3: Deepening

```text
User: Technology comparison with TCO/ROI
↓
AI: Created technology comparison document
↓
User: More detailed platform comparison
↓
AI: Created in-depth decision analysis
```

**Observation:** Each iteration built on the previous one — "continuous coherence" in action.

---

## 3. Session Metrics

| Metric | Value |
| ------ | ----- |
| Session duration | ~4 hours |
| Document iterations | 8 |
| Generated diagrams | 15+ (Mermaid) |
| Lines of documentation | ~2000 |
| External sources | 4 (anselm.ing pages) |
| Stakeholder questions | 12 (identified, not asked) |

---

## 4. ANSELM Workflow Compliance

| ANSELM Phase | Applied? | How? |
| ------------ | :------: | ---- |
| **Phase 1: Raw Ingestion** | ✅ | Paste requirements + data → AI synthesis |
| **Phase 2: Iterative Reasoning** | ✅ | Multiple prompts with refinement |
| **Phase 3: Formalizing** | ✅ | Mermaid generation from conversation |
| **Phase 4: Coherence** | ✅ | Validation with each change |

---

## 5. Key Moments

### 5.1 "Knowledge-First" Moment

Instead of starting with an architecture diagram, AI first built a "mental model":

- Stakeholders (agency staff, external entities, oversight bodies)
- Constraints (on-premise, ~200 users, PostgreSQL)
- Volumes (tens of thousands of documents annually)

Only then did architectural variants emerge.

### 5.2 "Disposable Views" Moment

ASCII diagrams were completely replaced with Mermaid without "regret" — they weren't the source of truth, just views.

### 5.3 "AI as Co-Pilot" Moment

When comparing platform options, AI proposed a decision framework (scenarios based on team composition) instead of a simple comparison table — "reasoning over drawing".

---

## 6. Conclusions

### What Worked

1. **"Use ANSELM" prompt** changed the framing of the entire session
2. **Iterativeness** allowed for progressive deepening
3. **No attachment to artifacts** enabled quick pivots

### What Required Adaptation

1. **No checklist** — AI had to interpret "what's next" on its own
2. **No formal "knowledge graph"** — context in session memory
3. **Validation** — relying on markdownlint as a proxy for "coherence"

---

*Complexity seeking clarity.*
