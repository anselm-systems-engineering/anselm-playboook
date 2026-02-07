# Business Case: Log Collector Architecture for Financial Institution

> **Type:** Success Reference  
> **Domain:** Banking / Financial Services  
> **Regulatory Context:** DORA (Digital Operational Resilience Act)  
> **Team Size:** 5 specialists (interdisciplinary)  
> **Duration:** Analytical Phase: 4 weeks → Deliverables ready for implementation  

---

## Executive Summary

A major development bank required a comprehensive log collection and analysis platform to achieve compliance with EU DORA regulation. Using Knowledge-First, AI-Partnered approach (precursor to ANSELM methodology), a 5-person team delivered complete architectural documentation in 4 weeks — a task that traditionally takes 3-6 months with conventional methods.

**Key Outcomes:**

- 📄 166 KB High-Level Design document (ISO/IEC/IEEE 42010 compliant)
- 📊 77 KB Feasibility Study with 3-year TCO analysis
- 💰 Recommended solution: ~10M PLN vs alternatives at ~40M PLN (75% cost reduction)
- ✅ Full DORA compliance mapping across 4 critical areas
- 🚀 Implementation roadmap with detailed task breakdown

---

## The Challenge

### Business Context

The financial institution faced a regulatory deadline for DORA compliance, requiring:

1. **Capacity Management** (Art. 9) — monitoring, measuring, forecasting ICT capacity
2. **Physical Access Control** (Art. 21) — mechanisms for physical security monitoring
3. **Logical Access Control** (Art. 8) — user activity and authorization logging
4. **Network Traffic Monitoring** (Art. 10) — continuous network observability

### Technical Complexity

- Heterogeneous environment: core banking, payment systems, HSM, containers, virtualization
- 41 critical applications requiring integration
- 5.5 TB/day log volume with 15-20% annual growth
- Existing fragmented monitoring tools (silos)
- Multiple stakeholder departments with competing concerns

### Traditional Approach Limitations

Conventional architecture methods would require:

- 3-6 months for stakeholder alignment and requirements gathering
- Separate teams for business analysis, technical architecture, cost modeling
- Multiple iteration cycles for variant analysis
- Risk of "analysis paralysis" or premature solution commitment

---

## The Approach: Knowledge-First, AI-Partnered

### Phase 1: Domain Knowledge Capture (Week 1)

Instead of starting with solution architecture, the team focused on **understanding the problem domain**:

| Knowledge Area | Artifact Created |
| -------------- | ---------------- |
| Organizational structure | Stakeholder map with influence/interest matrix |
| Regulatory landscape | DORA article mapping to technical controls |
| Existing capabilities | Current tool inventory and gap analysis |
| Business impact | BIA (Business Impact Analysis) scenarios |

**Key insight:** Domain knowledge was captured in plain Markdown files, not formal modeling tools. This allowed rapid iteration and AI-assisted analysis.

### Phase 2: AI-Partnered Analysis (Week 2)

The team used AI as a thinking partner (not just a code generator):

```text
Human expertise          AI contribution
─────────────────────    ─────────────────────
Domain knowledge    →    Pattern recognition
Regulatory context  →    Compliance mapping
Cost constraints    →    TCO modeling
Risk assessment     →    Scenario analysis
```

**Critical practice:** AI conversation logs were preserved as artifacts, creating an audit trail of reasoning. This proved invaluable for stakeholder questions about "why this recommendation?"

### Phase 3: Variant Analysis (Week 3)

Three implementation variants were evaluated:

| Variant | Description | 3-Year TCO | DORA Score |
| ------- | ----------- | ---------- | ---------- |
| A | Elastic Stack extension (hybrid) | ~10M PLN | 4.30/5 |
| B | Full Splunk consolidation | ~40M PLN | 3.30/5 |
| C | Status quo / minimal changes | ~7M PLN | 2.60/5 |

**Weighted scoring** across 10 criteria (regulatory compliance, TCO, scalability, risk, productivity, vendor independence, team competency, governance, investment phasing).

**Result:** Variant A recommended with clear, traceable justification.

### Phase 4: Deliverable Generation (Week 4)

Knowledge Packets → structured documentation:

- **HLD (High-Level Design)** — ISO 42010 compliant architecture description
- **Feasibility Study** — business case with ROI analysis
- **Appendices** — DORA mapping matrices, cost tables, glossary
- **MVP Roadmap** — 10 detailed implementation tasks

---

## Deliverable Quality

### Architecture Document Characteristics

The HLD document demonstrates ANSELM principles:

1. **Stakeholder-Centric Structure**
   - Explicit stakeholder catalog with concerns
   - Multiple architectural viewpoints (business, application, technology)
   - Traceability from concerns to design decisions

2. **Knowledge Transparency**
   - Assumptions explicitly stated and numbered
   - Constraints documented (regulatory, organizational, technical)
   - Reasoning visible in variant analysis

3. **Actionable Detail**
   - Specific technology recommendations with versions
   - Capacity planning with node counts and configurations
   - Cost breakdown to component level

### Sample Metrics

| Metric | Value |
| ------ | ----- |
| Document completeness | ISO 42010 full compliance |
| Stakeholder coverage | 7 department groups mapped |
| DORA article coverage | 12 articles with control mapping |
| Cost model granularity | Line-item CAPEX/OPEX breakdown |
| Risk identification | 15 risks with mitigation strategies |
| KPI definitions | 8 measurable success criteria |

---

## Why This Approach Worked

### 1. Knowledge Before Architecture

Traditional trap: Jump to solution → discover requirements gaps → rework.

ANSELM approach: Build domain understanding → solutions emerge from knowledge → minimal rework.

### 2. AI as Reasoning Partner

Not used for: Generating boilerplate, writing code, replacing expertise.

Used for: Pattern recognition, consistency checking, exploring alternatives, documentation structuring.

### 3. Markdown as Knowledge Medium

Benefits observed:

- Version control (Git) provided change history
- AI tools could process and analyze content
- Export to PDF for formal delivery
- No vendor lock-in to modeling tools

### 4. Emergent Structure

The team didn't follow a rigid template. Structure emerged from the problem:

```text
Organic evolution:
Context docs → Analysis artifacts → Decision records → Formal deliverables
```

This mirrors how experts actually think, not how methodologies prescribe thinking.

---

## Lessons Learned

### What Worked Well

✅ **Preserving AI conversations** — Became invaluable for explaining reasoning to stakeholders

✅ **Stakeholder mapping early** — Prevented late-stage "we weren't consulted" objections

✅ **Variant analysis with weights** — Made recommendation defensible and transparent

✅ **Incremental documentation** — No "big bang" document creation at the end

### What Could Be Improved

⚠️ **More structured knowledge indexing** — Finding specific information required manual search

⚠️ **Explicit phase boundaries** — Team sometimes unclear "where are we in the process?"

⚠️ **Template starting points** — Some documents were built from scratch unnecessarily

---

## Quantified Value

### Time Efficiency

| Activity | Traditional | ANSELM Approach | Improvement |
| -------- | ----------- | --------------- | ----------- |
| Stakeholder analysis | 3-4 weeks | 1 week | 70% faster |
| Variant evaluation | 4-6 weeks | 1 week | 80% faster |
| Document creation | 4-8 weeks | 2 weeks | 65% faster |
| **Total** | **11-18 weeks** | **4 weeks** | **~75% faster** |

### Quality Indicators

- Zero major revision cycles after stakeholder review
- Recommendation accepted without modification
- Implementation team reported "clearest architecture document we've received"

### Cost Avoidance

The rigorous variant analysis prevented selection of a 40M PLN solution when a 10M PLN alternative provided equal or better regulatory compliance.

**Decision quality ROI:** 30M PLN saved through better analysis.

---

## Applicability

This approach is particularly effective for:

| Context | Why It Works |
| ------- | ------------ |
| **Regulatory compliance projects** | Complex requirement mapping benefits from knowledge-first analysis |
| **Multi-stakeholder environments** | Explicit concern tracking prevents misalignment |
| **Technology selection decisions** | Transparent variant analysis supports defensible choices |
| **Time-pressured initiatives** | AI partnership accelerates without sacrificing quality |
| **Interdisciplinary teams** | Shared Markdown artifacts bridge expertise gaps |

---

## Conclusion

This project demonstrated that Knowledge-First, AI-Partnered methods can deliver enterprise-grade architecture documentation in a fraction of traditional timeframes — without sacrificing quality or traceability.

The success wasn't due to tools or templates, but to a **way of thinking**:

> Understand deeply before designing. Partner with AI for reasoning, not just production. Make knowledge explicit and traceable.

This is the essence of what became the ANSELM methodology.

---

*This business case is anonymized. The project was real, delivered for a major Polish bank in 2025.*
