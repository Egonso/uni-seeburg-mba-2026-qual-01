---
name: uni-seeburg-mba-qual-01
description: "Use this skill when working in the Uni Seeburg MBA 2026 QUAL-01 repository on a qualitative empirical MBA thesis, including research-question alignment, interview design, sampling, qualitative analysis, assessment-rubric optimization, public-data boundaries, source validation, KI usage logging, and high-quality academic review."
---

# Uni Seeburg MBA QUAL-01 Skill

## Purpose

This skill guides a Codex agent that supports a qualitative empirical MBA thesis in this repository.

The agent's job is to make qualitative work methodically serious: precise question, theory-to-interview mapping, defensible sample, transparent interview guide, documented analysis, traceable findings, cautious discussion, and clean assessment mapping.

The agent must not fabricate data, invent interviews, smooth contradictions, or write final thesis passages that hide the student's own work.

## Public Boundary

This repository is temporarily public. Keep it public-safe.

Never commit:

- student names, private contact data, IDs, signatures or approval documents.
- interview partner names, target lists, e-mails, recordings, transcripts, quotes or raw codes.
- WhatsApp exports, private feedback, forms, videos, module materials or internal notes.
- concrete unpublished company, platform, prompt, screenshot or process data.
- complete Lernplattform PDFs or copyrighted full-text copies.
- invented sources, invented interview findings or KI-generated bibliography entries.

Always use real Umlaute: ä, ö, ü.

If interview planning or data analysis needs real people or private material, keep it out of the public repo and ask for private import after visibility is changed.

## Required Start Sequence

Before substantial work, read:

1. `README.md`
2. `AGENTS.md`
3. `docs/00-publication-boundary.md`
4. `docs/01-12-schritte-outline-gate.md`
5. `workspace/01_expose_und_forschungsfrage/BIG_STORY.md`
6. `workspace/01_expose_und_forschungsfrage/FORSCHUNGSFRAGEN.md`
7. `workspace/01_expose_und_forschungsfrage/OUTLINE.md`
8. `workspace/01_expose_und_forschungsfrage/SCOPE_UND_NICHT_THEMEN.md`
9. `workspace/01_expose_und_forschungsfrage/BEWERTUNGS_MAPPING.md`
10. `workspace/02_literatur/QUELLENMATRIX.md`
11. `workspace/03_methodik/METHODIK.md`
12. `KI_NUTZUNGSLOG.md`

If files are placeholders, improve the scaffold before creating interview or result text.

## Current Work Type

Treat QUAL-01 as a qualitative empirical thesis.

The core contribution should come from qualitative data interpreted through a theoretical frame. Literature is necessary, but it is not the whole method. A framework or recommendations may emerge in the discussion, but they cannot replace data collection and analysis.

Default qualitative chain:

```text
problem -> research question -> theory concepts -> interview guide -> sampling -> interviews -> transcripts/notes -> coding/categories -> findings -> discussion -> contribution and implications
```

Every link must be visible.

## Assessment Logic

Use the empirical-work rubric as the primary benchmark.

| Area | Points | What the agent must optimize |
|---|---:|---|
| Introduction | 15 | developed problem, clear and relevant research question, motivation |
| Theory | 25 | clear theoretical frame, defined core concepts, literature-derived logic |
| Method and results | 25 | suitable method, rigor, matching collection and analysis, understandable findings |
| Discussion and contribution | 25 | explicit answer, appropriate interpretation, alternatives, contribution, implications |
| Formalia | 10 | language, layout, figures, tables, citations, bibliography |

Secondary plausibility check:

- A general thesis schema may appear in older or broader materials with this rough logic: structure 10 points, theory 30 points, empirical work 30 points, discussion and management implications 20 points, formalia 10 points.
- For QUAL-01 this is only secondary, because the empirical-work rubric above is the primary path.
- Use it to check whether empirical work and discussion are strong enough, not merely present.
- Very-good level starts at 87.5 points in the general schema. Treat this as a quality bar, not as a promise of grade.

Every review must answer:

- Is the qualitative phenomenon clear?
- Does the theory explain why interviews are useful?
- Does every interview block map to a research or subquestion?
- Are sampling and access defensible?
- Are findings more than opinion summaries?
- Are alternatives and limits included?

## 1er Benchmark Logic

Use public 1er-range Seeburg references as quality markers:

| Benchmark | Public note | Transfer to QUAL-01 |
|---|---|---|
| Weber 2021, Note 1,0 | qualitative expert interviews, Mayring-style analysis, technology/business topic | strongest benchmark for empirical qualitative structure and discussion discipline |
| Hesse 2015, Note 1,3 | conceptual evaluation with stakeholder logic | useful for discussion and implication structure |
| Schiele 2015, Note 1,3 | strong construct and measurement logic | only secondary, but useful for construct clarity before data collection |

Do not copy contents. Use these as standards for clear problem, method transparency, traceable results and explicit limitations.

## Work Gates

### Gate 1: Research Question

Do not design interviews until:

- the qualitative phenomenon is precise.
- the research question asks about experiences, perceptions, evaluation logics, decision practices, meanings or professional handling.
- subquestions can be translated into interview blocks.
- the scope is realistic for 20 to 40 pages.
- the work does not imply quantitative claims without quantitative data.

Bad qualitative questions ask "how much" or "what effect" without appropriate data. Good qualitative questions ask how actors perceive, interpret, evaluate, justify, handle or translate a change.

### Gate 2: Theory

The theory chapter must:

- define core concepts.
- explain the field enough to interpret interviews.
- avoid becoming a tool or market overview.
- produce lenses for interview design and later analysis.
- identify uncertainties that interviews can illuminate.

Each key concept should map to an interview block or discussion lens.

### Gate 3: Method

`workspace/03_methodik/METHODIK.md` must specify:

- research design.
- target group.
- sampling logic and inclusion criteria.
- planned interview form.
- interview guide structure.
- transcription or note-taking approach.
- coding or analysis method.
- qualitative quality criteria.
- data protection and anonymization.

If these are empty, fill them before drafting any result chapter.

### Gate 4: Interview Guide

Every interview block must map to:

- research question or subquestion.
- theoretical concept.
- expected analytical use.
- open, non-leading question wording.

Prefer prompts that invite concrete situations:

- "Beschreiben Sie eine Situation, in der ..."
- "Woran merken Sie, dass ..."
- "Wie entscheiden Sie, ob ..."
- "Welche Unterschiede sehen Sie zwischen ..."
- "Wo stoßen Ihre bisherigen Mess- oder Bewertungslogiken an Grenzen?"

Avoid:

- questions that already contain the desired answer.
- yes/no questions as primary prompts.
- tool-promo language.
- asking interviewees to validate the student's preferred framework too early.

### Gate 5: Analysis

Before writing findings:

- anonymize data.
- document transcription or note status.
- define initial coding logic.
- preserve contradictions and counterexamples.
- separate first-order statements from second-order interpretation.
- map categories back to subquestions.
- select quotes only after anonymization and permission boundaries are clear.

Findings must not be a chain of interview summaries. They need categories, patterns, tensions, examples and boundaries.

### Gate 6: Discussion

Discussion must:

- answer each subquestion explicitly.
- connect findings to theory.
- name alternative explanations.
- avoid causal, ROI, market-size or effectiveness claims unless the data supports them.
- state contribution to research and management practice.
- include limitations: sample, access, context, time, researcher role, platform/tool dependence if relevant.

### Gate 7: Final Readiness

Before calling a draft ready:

- research question is answered.
- sample and method are transparent.
- results are traceable to data.
- no private interview data is in the public repo.
- tables and figures are meaningful.
- all sources are verified.
- KI use is logged.
- final wording remains student-owned.

## Qualitative Quality Markers

Use these markers when reviewing:

- Gegenstandsangemessenheit: method fits the phenomenon.
- theoretical grounding: categories connect to literature.
- plausible saturation logic: enough interviews for the scope or honest limitation.
- auditability: reader can follow collection and analysis.
- textuelle Performanz: findings are written clearly and analytically.
- originality: contribution is more than a practical opinion roundup.

## Literature Matrix

`workspace/02_literatur/QUELLENMATRIX.md` should include:

- source.
- field.
- core concept.
- definition.
- relevance to research question.
- use in theory.
- use in interview guide.
- use in discussion.
- limitation.
- quality judgment.

Literature is used to design the inquiry and interpret data. It does not replace data.

## Review Output Format

Use this structure:

```text
Stärken
- ...

Risiken
- ...

Konkrete Änderungen
- ...

Quellen nachziehen
- ...

Bewertungsraster-Abdeckung
- ...

Nächster Schritt
- ...
```

Refer to exact file names, headings, missing rows and unresolved method decisions.

## KI Documentation

For meaningful agent support, update or request an update to `KI_NUTZUNGSLOG.md`:

- date.
- tool or agent.
- purpose.
- input category.
- output category.
- human review.
- adopted or not.

For qualitative work, the log must not expose private interview data. Use categories like "anonymized excerpt" or "public scaffold", not real names or raw quotes.

## Formalia Reminders

Public-safe assumptions:

- target main text: 20 to 40 pages unless confirmed otherwise.
- current dates: presentation registration 2026-06-20, supervisor approval 2026-06-25, presentation upload 2026-06-26, colloquium 2026-06-27, latest thesis submission 2026-09-10.
- final submission format must still be confirmed if not documented.
- use the MBA thesis template for private drafting.
- agent must never fake signatures, declarations, approvals or interview consent.

## Stop Conditions

Stop and ask for human or private-context action when:

- the repository is public and real interview material is needed.
- interview participants, quotes or transcripts would be exposed.
- the method type is being changed.
- a source cannot be verified.
- a finding is being claimed without data.
- a supervisor, examination office or student decision is required.
