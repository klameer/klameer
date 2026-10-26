# Karim Lameer

**Finance systems, Anaplan architecture and applied AI.** CIMA-qualified
accountant and Master Anaplanner, with fifteen years in FP&A and planning
systems. I run [CodelessOps](https://codelessops.com), where I automate the
finance work teams still do by hand, with a person signing off every step
that matters. The tools below help finance teams understand their models,
review changes and trace an AI-generated answer back to its evidence.

I'm interested in roles combining finance domain knowledge, solution
architecture and hands-on delivery. The projects show the work: working
examples, implementation choices, tests and the limits of what has been
validated. The [writing](#writing) shows the thinking behind them.

## Experience behind the projects

My work spans finance operations, planning architecture and implementation
across biotech, pharma, media and other reporting-heavy organisations.

- **Close and forecasting:** at a listed clinical-stage biotech, I built
  the Anaplan planning platform and automated its data loads. The mechanical
  close fell from 12 working days to under 8 hours, and reforecasting from
  a week to a day. Here, mechanical close means ledger close through to
  consolidated actuals ready for review. My
  [delivery case study](https://codelessops.com/posts/twelve-days-to-eight-hours/)
  explains the scope, integrations and handover.
- **Invoices and contracts:** at a media group, I took invoice processing
  from over 60 hours a month to about 2, and built a contract-review
  extraction pipeline that handles hundreds of contracts a run, with a
  person validating every output.
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
| **[Anaplan Estate](https://github.com/klameer/anaplan-estate)** | What should we investigate in an inherited estate, and what could a change affect? | [Try the report](https://anaplan-estate.codelessops.com), [case study](https://github.com/klameer/anaplan-estate/blob/master/CASE_STUDY.md), [validation limits](https://github.com/klameer/anaplan-estate/blob/master/VALIDATION.md). The free check behind [Anaplan Architect](https://codelessops.com/anaplan-architect/). |
| **[Anaplan Grammar](https://github.com/klameer/anaplan-grammar)** | How do we analyse formula structure and dependencies reliably? | [Parser and graph](https://github.com/klameer/anaplan-grammar/tree/master/src/anaplan_grammar), [public regression tests](https://github.com/klameer/anaplan-grammar/tree/master/tests), [engineering walkthrough](https://github.com/klameer/anaplan-grammar/blob/master/ENGINEERING.md). |
| **[Verified Close](https://github.com/klameer/verified-close)** | Can Claude run a month-end close where a script computes every figure, a named reviewer signs every step and an auditor can follow the trail? | [Recorded run](https://github.com/klameer/verified-close/blob/main/showcase/may-26/TRANSCRIPT.md), [how the close works](https://github.com/klameer/verified-close#how-the-close-works), [what the tests prove](https://github.com/klameer/verified-close#what-the-tests-prove). A Claude Code plugin built on Anthropic's finance skills. Fictional data. |
| **[Grounded field notes](https://github.com/klameer/grounded-field-notes)** | What does it take to operate a finance document assistant? | [Case study](https://github.com/klameer/grounded-field-notes/blob/main/CASE_STUDY.md), [architecture decisions](https://github.com/klameer/grounded-field-notes/tree/main/docs/adr), [incidents](https://github.com/klameer/grounded-field-notes/blob/main/docs/incidents.md), [my contribution and upstream work](https://github.com/klameer/grounded-field-notes/blob/main/PROVENANCE.md). Documentation only; application code is private. [What Grounded does](https://codelessops.com/grounded/). |

## Writing

I write at [codelessops.com](https://codelessops.com/posts/) about AI and
automation for finance, in plain language, for people whose numbers face a
board, an auditor or a regulator. Start with these three:

- [Citations aren't verification](https://codelessops.com/posts/what-is-verifiable-ai/): what it takes for an AI answer to be checkable, not just referenced.
- [Continuous close for FP&A](https://codelessops.com/posts/continuous-close-fpa/): a three-part series on the zero-day close and how to build one with mainstream AI tools.
- [Anaplan Estate: what it finds and how to use it](https://codelessops.com/posts/anaplan-estate-walkthrough/): a walkthrough of the estate review on a fictional estate.

Latest posts, updated automatically:

<!-- BLOG-POST-LIST:START -->
- 23 Oct 2026 · [What Anthropic's finance plugin leaves to you](https://codelessops.com/posts/anthropic-finance-plugin/)
- 19 Oct 2026 · [The seams map](https://codelessops.com/posts/the-seams-map/)
- 7 Oct 2026 · [Continuous close for FP&A](https://codelessops.com/posts/continuous-close-fpa/)
- 7 Oct 2026 · [What a continuous close is, and why to aim at zero days](https://codelessops.com/posts/continuous-close-fpa/what-is-it/)
- 7 Oct 2026 · [The use case: a contract signed on the 6th, on the forecast by the 8th](https://codelessops.com/posts/continuous-close-fpa/the-use-case/)
<!-- BLOG-POST-LIST:END -->

[All posts](https://codelessops.com/posts/) · [The public record](https://codelessops.com/projects/), a dated feed of everything shipped.

## How I approach the work

- Start with the finance process, its users and the decision the output must support.
- Make calculations and source references inspectable; keep human judgment explicit.
- Test against known answers and failure cases, and record what remains unproven.
- Explain the architecture, rejected alternatives and operational consequences.

The Anaplan parser was developed against a large private corpus of real
formulas. The public tests use fictional formulas; the private result is
not independently reproducible from this GitHub. Estate recommendations
still need validation on unseen estates. Verified Close runs on one
fictional company. Each repository gives the evidence and scope behind its
claims.

## Also on GitHub

[The Audited AI Close](https://github.com/klameer/audited-ai-close), the
earlier close kit that runs on a standard claude.ai licence ·
[The Board Pack Test](https://github.com/klameer/test-your-finance-llm), the
question set I use to evaluate Grounded ·
[Anaplan Diff](https://github.com/klameer/anaplan-diff) ·
[Impact Explorer](https://github.com/klameer/anaplan-impact-analysis) ·
[API Starter](https://github.com/klameer/anaplan-api-starter) ·
[Anaplan Clock](https://github.com/klameer/Anaplan-Clock)

## Contact and background

[LinkedIn — experience and contact](https://www.linkedin.com/in/karimlameer) ·
[CodelessOps](https://codelessops.com): [hire me](https://codelessops.com/hire/) ·
[book a call](https://codelessops.com/karim/)
