# Contributing to ANSELM Playbook

Thank you for your interest in contributing! This document explains how to participate.

## Ways to Contribute

### 1. Add a Case Study

We especially welcome real-world case studies. Your case study should include:

**Required:**

- Context (domain, scale, constraints)
- How ANSELM was applied
- What worked / what didn't
- At least 2 Knowledge Cells

**Optional:**

- AI model used
- Templates created
- Metrics (time saved, alternatives explored)

**Anonymization:**
If your project is confidential, anonymize it:

- Replace organization names with descriptions ("A financial services company")
- Generalize specific numbers to ranges
- Remove identifying details while preserving methodology insights

**Directory structure:**

```text
case-studies/
└── your-case-study/
    ├── README.md           # Overview
    └── knowledge-cells/
        ├── xxx.md
        └── yyy.md
```

### 2. Improve Templates

Templates should be:

- Generic enough for any domain
- Specific enough to be useful
- Well-documented with placeholders

Submit improvements via PR with explanation of changes.

### 3. Add Patterns or Anti-Patterns

If you've discovered a pattern that works (or doesn't), add it to `playbook/patterns/ANSELM-Patterns.md`:

**Pattern format:**

```markdown
### Pattern N: [Name]

**Context:** [When this applies]

**Problem:** [What challenge it addresses]

**Solution:** [How to apply it]

**Consequences:**
- ✅ [Benefit]
- ⚠️ [Trade-off]
```

### 4. Integration Guides

Help bridge ANSELM with existing frameworks:

- TOGAF ADM integration
- SAFe alignment
- SysML/UAF mapping
- ArchiMate compatibility

Add to `integrations/` directory.

### 5. Translations

We welcome translations of the Playbook. Create a directory:

```text
playbook/
└── translations/
    └── de/          # German
    └── ja/          # Japanese
    └── pl/          # Polish
```

## Contribution Process

### For Small Changes

1. Fork the repository
2. Make your changes
3. Submit a Pull Request
4. Describe what you changed and why

### For Large Contributions

1. Open an Issue first to discuss
2. Get feedback on approach
3. Then submit PR

### For Case Studies

1. Open an Issue titled "Case Study: [Domain/Description]"
2. We'll confirm it fits the repository scope
3. Submit PR with full case study

## Style Guide

### Markdown

- Use ATX headings (`#`, `##`, `###`)
- One sentence per line (easier diffs)
- Use fenced code blocks with language tags
- Tables: use `| --- |` separator style

### Diagrams

- Prefer Mermaid (renders on GitHub)
- Keep diagrams simple (5-9 elements)
- Include alt-text description

### Tone

- Practical over theoretical
- Specific over vague
- Humble over authoritative ("we found" not "you must")

## Code of Conduct

- Be respectful and constructive
- Assume good intent
- Focus on ideas, not people
- Welcome newcomers

## Recognition

Contributors will be acknowledged in:

- README.md acknowledgments section
- Case study attributions (if desired)
- Release notes

## Questions?

- Open an Issue with tag `question`
- Or start a Discussion

---

*Complexity seeking clarity, together.*
