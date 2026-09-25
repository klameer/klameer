# Karim Lameer

**Finance systems, Anaplan architecture and applied AI.** CIMA-qualified
accountant and Master Anaplanner, with fifteen years in FP&A and planning
systems. I build tools that help finance teams understand their models,
review changes and trace an AI-generated answer back to its evidence.

I'm interested in roles combining finance domain knowledge, solution
architecture and hands-on delivery. The projects below show the work:
working examples, implementation choices, tests and the limits of what has
been validated.

## Experience behind the projects

My work spans finance operations, planning architecture and implementation
across biotech, pharma and other reporting-heavy organisations.

- **Close and forecasting:** at a listed clinical-stage biotech, I built
  the Anaplan planning platform and automated its data loads. The mechanical
  close fell from 12 working days to under 8 hours, and reforecasting from
  a week to a day. Here, mechanical close means ledger close through to
  consolidated actuals ready for review. My
  [delivery case study](https://codelessops.com/posts/twelve-days-to-eight-hours/)
  explains the scope, integrations and handover.
- **Professional background:** CIMA-qualified Management Accountant,
  Master Anaplanner and MSc in Information Technology from Keele University.
  [Background and experience](https://codelessops.com/about/).
- **Other perspectives:** Anaplan featured my career and approach in
  [Meet Solutions Architect Karim Lameer](https://www.linkedin.com/posts/anaplan_meet-solutions-architect-karim-lameer-activity-6968948608922501121-5uJv).
  [LinkedIn recommendations](https://www.linkedin.com/in/karimlameer/)
  from colleagues describe my Anaplan delivery, financial understanding
  and ability to become productive quickly in a team.

## Start with these projects

| Project | Problem it addresses | Evidence to inspect |
| --- | --- | --- |
| **[Anaplan Estate](https://github.com/klameer/anaplan-estate)** | What should we investigate in an inherited estate, and what could a change affect? | [Try the report](https://anaplan-estate.codelessops.com), [case study](https://github.com/klameer/anaplan-estate/blob/master/CASE_STUDY.md), [validation limits](https://github.com/klameer/anaplan-estate/blob/master/VALIDATION.md). |
| **[Anaplan Grammar](https://github.com/klameer/anaplan-grammar)** | How do we analyse formula structure and dependencies reliably? | [Parser and graph](https://github.com/klameer/anaplan-grammar/tree/master/src/anaplan_grammar), [public regression tests](https://github.com/klameer/anaplan-grammar/tree/master/tests), [engineering walkthrough](https://github.com/klameer/anaplan-grammar/blob/master/ENGINEERING.md). |
| **[The Audited AI Close](https://github.com/klameer/audited-ai-close)** | How can an assistant coordinate a month-end close with calculation checks and human review? | [Case study](https://github.com/klameer/audited-ai-close/blob/main/CASE_STUDY.md), [calculation scripts](https://github.com/klameer/audited-ai-close/tree/main/skills/close-pack), [finance-team runbook](https://github.com/klameer/audited-ai-close/blob/main/handover/RUNBOOK.md). Fictional data. |
| **[The Board Pack Test](https://github.com/klameer/test-your-finance-llm)** | Can an AI system answer questions across realistic finance documents and supply the right sources? | 34 documents, 25 questions, saved answers and [versioned grading checks](https://github.com/klameer/test-your-finance-llm/tree/main/grading). Results distinguish automatic checks from human judgment. |
| **[Grounded field notes](https://github.com/klameer/grounded-field-notes)** | What does it take to operate a finance document assistant? | [Case study](https://github.com/klameer/grounded-field-notes/blob/main/CASE_STUDY.md), [architecture decisions](https://github.com/klameer/grounded-field-notes/tree/main/docs/adr), [incidents](https://github.com/klameer/grounded-field-notes/blob/main/docs/incidents.md), [my contribution and upstream work](https://github.com/klameer/grounded-field-notes/blob/main/PROVENANCE.md). Documentation only; application code is private. |

## How I approach the work

- Start with the finance process, its users and the decision the output must support.
- Make calculations and source references inspectable; keep human judgment explicit.
- Test against known answers and failure cases, and record what remains unproven.
- Explain the architecture, rejected alternatives and operational consequences.

The Anaplan parser was developed against 13,214 unique private formulas.
The public tests use fictional formulas; the private corpus result is not
independently reproducible from this GitHub. Estate recommendations still
need validation on unseen estates. The AI close is a fictional reference
workflow, and the Board Pack Test covers one company. Each repository gives
the evidence and scope behind its claims.

## Smaller tools

[Anaplan Diff](https://github.com/klameer/anaplan-diff) ·
[Impact Explorer](https://github.com/klameer/anaplan-impact-analysis) ·
[API Starter](https://github.com/klameer/anaplan-api-starter) ·
[Anaplan Clock](https://github.com/klameer/Anaplan-Clock)

## Contact and background

[LinkedIn — experience and contact](https://www.linkedin.com/in/karimlameer) ·
[CodelessOps — projects and writing](https://codelessops.com)
