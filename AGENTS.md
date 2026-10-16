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

When both workflows apply:

1. Use `academic-literature-route` for literature discovery and bibliographic verification.
2. Use `academic-research-suite` for evidence synthesis, literature-review structure, claim auditing, and research-gap analysis.
3. Verified full-text evidence overrides summaries, metadata-only evidence, and model prior knowledge.

Academic accuracy rules:

- Never invent papers, authors, journals, DOI values, samples, methods, results, mechanisms, or causal claims.
- Distinguish correlation, association, mechanism/channel evidence, and causal identification.
- Do not upgrade proxy evidence into direct evidence.
- If a claim is unsupported by the supplied or verified source, explicitly mark it as unsupported or requiring verification.
- User-provided verified full text and explicit evidence classifications take priority over generic assumptions.

Do not automatically execute either Skill for unrelated coding or repository-maintenance tasks.
