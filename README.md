# Karim Lameer

I build AI systems for finance teams. CIMA-qualified accountant, Master
Anaplanner, fifteen years in FP&A and planning systems. My rule for all of
it: an auditor has to be able to follow what the machine did. Every figure
scripted, every step signed off, every claim traced back to a document.

Two threads run through everything here. Anaplan tooling built from the
standard exports, so it runs on your own machine and nothing leaves it. And
AI for finance work that holds up under audit.

## Anaplan tooling

Anaplan has no published grammar for its formula language, so I wrote one.
Everything else in this section sits on top of it.

| Repo | What it answers |
| --- | --- |
| **[anaplan&#8209;grammar](https://github.com/klameer/anaplan-grammar)** | A formal grammar and parser for Anaplan formulas, reverse-engineered from Anapedia and 13,214 production formulas (all 13,214 parse and round-trip). Dependency graph checked against Anaplan's own Referenced By column, plus diff, lint and a health report. `pip install`, zero dependencies. |
| **[anaplan&#8209;estate](https://github.com/klameer/anaplan-estate)** | Find what to improve in Anaplan and see what a change could affect. Point it at a folder of exports and get one offline HTML report: action plan, change-impact explorer, evidence. Try it without installing anything at [anaplan-estate.codelessops.com](https://anaplan-estate.codelessops.com). |
| [anaplan&#8209;diff](https://github.com/klameer/anaplan-diff) | What changed between two builds? Modules and formulas added, removed and changed, from two line item exports. |
| [anaplan&#8209;impact&#8209;analysis](https://github.com/klameer/anaplan-impact-analysis) | What breaks if I change this? Click a line item and see the downstream chain. One HTML file, runs in the browser. |
| [anaplan&#8209;api&#8209;starter](https://github.com/klameer/anaplan-api-starter) | The whole v2 API loop in one Python file. Auth, names to IDs, upload, run, poll, download to pandas. |
| [Anaplan-Clock](https://github.com/klameer/Anaplan-Clock) | Gives a model the current date and time, so formulas can stamp actions and flag stale data. |

`anaplan-estate` ships with a fictional estate you can run end to end and a
note listing what was planted in it and what the tool finds. Neither repo
claims accuracy or savings; what has and has not been validated is written
down in each one.

## AI for finance that holds up under audit

- **[The Board Pack Test](https://github.com/klameer/test-your-finance-llm)**:
  a public, verifiable benchmark for AI agents on realistic finance work.
  Bring your own board pack and see what your model actually gets right.
- **[The Audited AI Close](https://github.com/klameer/audited-ai-close)**:
  a complete month-end close run by Claude, with a human reviewer gate at
  every step and a sealed audit binder at the end. Fictional data, MIT.
- **[Grounded field notes](https://github.com/klameer/grounded-field-notes)**:
  the engineering record behind [Grounded](https://codelessops.com), a
  production RAG system for finance teams. Decision records, architecture,
  evals, cost and latency, and the incidents that shaped them. Text only.

## Elsewhere

- [codelessops.com](https://codelessops.com), where I write about AI in
  finance and what holds up under audit
- [LinkedIn](https://www.linkedin.com/in/karimlameer)
