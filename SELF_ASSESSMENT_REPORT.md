# Self-assessment — PA#1

Repository: https://github.com/bhuuthinh2005-design/Deadline-Extractor

Submitted by:
- 23127001 — Nguyễn Lê Quan Anh
- 23127121 — Bùi Hữu Thịnh

I claim: 81 / 100

| Criterion | Max | I claim | Evidence |
|---|---|---|---|
| Problem and users | 20 | 16 | PROPOSAL.pdf §1: named user (Linh, 2nd-year FIT-HCMUS), one-sentence problem, current workaround. Linh is a composite persona; we have not yet interviewed other students. |
| The LLM feature, and the cost of it being wrong | 25 | 21 | PROPOSAL.pdf §2: one feature (deadline extraction), JSON fields, who is affected, how much, undoable or not, and how we would know (gold set, false-late target). Targets are planned, not measured. |
| Scope: in and out | 15 | 13 | PROPOSAL.pdf §3: two-column in/out table; every in-scope item maps to a checkpoint in §4 (e.g. .ics and change/cancel linking in checkpoint 5). |
| Plan and ownership | 20 | 14 | PROPOSAL.pdf §4: six checkpoints, each with a named owner (A / T), a date and assigned work. Dates are our own working dates, not yet checked against the official course calendar. |
| Risks | 10 | 9 | PROPOSAL.pdf §5: R1 (no trustworthy gold set) and R2 (confident wrong dates), each with a mitigation that starts this week (30 messages each; 40 resolver unit tests). |
| Technology choices | 10 | 8 | PROPOSAL.pdf §6: one justification per choice, tied to the project; model provider and estimated cost (US$1–5, cap US$10). The price comes from a third-party summary and is not yet checked against the provider's own page. |
| **Total** | **100** | **81** | |

## What I did not manage

- The checkpoint dates are assumed; I did not have the course calendar, so they may need to move.
- No student has been interviewed yet and no gold-set messages have been collected, so the false-late and wrong-confident targets are untested.
- The model price should be re-checked against the provider's official pricing page.

## What I would do differently

Collect the first 30 real messages before writing the feature description, so the example phrasings and the cost-of-error argument come from data rather than from memory.
