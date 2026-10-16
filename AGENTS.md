# Research workflow

This repository contains local research workflow instructions under `.agents/skills/`.

When a task involves academic literature discovery, literature searching, bibliography verification, retrieval strategy, or candidate-paper screening:

1. Read:
   `.agents/skills/academic-literature-route/SKILL.md`
2. Follow that Skill's instructions and supporting files as applicable.
3. Treat search-engine, LLM, social-media, and webpage results as leads until bibliographic facts are verified from stable academic sources.

When a task involves literature review synthesis, structured evidence synthesis, research-gap analysis, claim-to-source auditing, academic review drafting, or evaluating relationships among papers:

1. Read:
   `.agents/skills/academic-research-suite/SKILL.md`
2. Follow the router and only read the additional ARS files required for the current task.
3. Do not load the entire ARS directory unnecessarily.

When a task involves economics or accounting academic writing, rewriting, paper structure, theory/mechanism exposition, empirical-method writing, identification-strategy explanation, results presentation, literature-review prose polishing, or academic style revision:

1. Read:
   `.agents/skills/econ-write/SKILL.md`
2. Read only the additional Econ Write companion files needed for the task:
   - `.agents/skills/econ-write/identification-strategies.md`
   - `.agents/skills/econ-write/latex-tips.md`
   - `.agents/skills/econ-write/review-checklist.md`
   - `.agents/skills/econ-write/specialized-tasks.md`
3. Use Econ Write primarily for:
   - economics/accounting academic prose
   - theory and mechanism exposition
   - empirical-design and identification-language precision
   - results presentation
   - structure and style improvement
4. Econ Write must NOT:
   - invent literature, data, coefficients, samples, methods, DOI values, mechanisms, robustness tests, or empirical findings;
   - change association/correlation into causality;
   - upgrade channel-support evidence into formal mediation;
   - convert proxy evidence into direct evidence;
   - override verified full-text evidence or explicit evidence classifications.

When literature discovery and evidence-synthesis workflows both apply:

1. Use `academic-literature-route` for literature discovery and bibliographic verification.
2. Use `academic-research-suite` for evidence synthesis, literature-review structure, claim auditing, and research-gap analysis.
3. Verified full-text evidence overrides summaries, metadata-only evidence, and model prior knowledge.

Evidence and workflow priority:

1. Verified source/full-text evidence and explicit user-provided classifications have highest priority.
2. `academic-literature-route` controls literature discovery and bibliographic verification.
3. `academic-research-suite` controls evidence synthesis, literature-review structure, claim auditing, and research-gap analysis.
4. `econ-write` improves economics/accounting exposition, structure, methods language, and style only after the evidentiary basis is established.

If instructions conflict, higher-priority evidence and workflow rules override lower-priority writing/style guidance.

When a task involves both literature synthesis and prose polishing, first use `academic-research-suite` for evidence synthesis and judgments, then use `econ-write` to improve the expression. Do not allow `econ-write` to change the evidence strength or research conclusions established by ARS.

Academic accuracy rules:

- Never invent papers, authors, journals, DOI values, samples, methods, results, mechanisms, or causal claims.
- Distinguish correlation, association, mechanism/channel evidence, and causal identification.
- Do not upgrade proxy evidence into direct evidence.
- If a claim is unsupported by the supplied or verified source, explicitly mark it as unsupported or requiring verification.
- User-provided verified full text and explicit evidence classifications take priority over generic assumptions.

Do not automatically execute any Skill for unrelated coding or repository-maintenance tasks.
