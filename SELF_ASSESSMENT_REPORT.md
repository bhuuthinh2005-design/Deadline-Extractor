# Self-assessment — PA#1

Repository: https://github.com/bhuuthinh2005-design/Deadline-Extractor

Submitted by:
- 23127001 — Nguyễn Lê Quan Anh
- 23127121 — Bùi Hữu Thịnh

I claim: 91 / 100

| Criterion | Max | I claim | Evidence |
|---|---|---|---|
| Problem and users | 20 | 18 | PROPOSAL.pdf §1: named user (Linh, 2nd-year FIT-HCMUS), concrete situation with real Vietnamese message examples, one-sentence problem, and current manual workarounds (Google Calendar/Notion/Zalo scroll). |
| The LLM feature, and the cost of it being wrong | 25 | 23 | PROPOSAL.pdf §2: one sharp feature (deadline extraction to JSON), clear architectural split (LLM relative expression vs deterministic resolver), asymmetric cost analysis (false-late penalty vs false-early effort; irreversible missed deadline), and evaluation plan with gold set (≥150 messages, false-late ≤ 2%, wrong-confident ≤ 3%). |
| Scope: in and out | 15 | 14 | PROPOSAL.pdf §3: explicit two-column in/out table; non-goals (no scraping, no OCR, no mobile app, no fine-tuning) prevent scope creep; all in-scope deliverables map to checkpoints in §4. |
| Plan and ownership | 20 | 17 | PROPOSAL.pdf §4: all six checkpoints fully covered, each with individual named owners (A / T, no generic "team" ownership) and specific deliverables matching the semester timeline. |
| Risks | 10 | 10 | PROPOSAL.pdf §5: two fatal project risks (R1: lack of reliable gold set; R2: model hallucinating relative dates with confidence), each with concrete mitigation starting this week (30 messages each + 25 synthetic cases; 40 resolver unit tests for edge cases). |
| Technology choices | 10 | 9 | PROPOSAL.pdf §6: concise one-line project-specific justifications for each stack element; explicit model provider (Gemini Flash-Lite), concrete token math (700 tok * 10k calls ≈ 7M tok ≈ US$1–5), and a US$10 semester budget cap. |
| **Total** | **100** | **91** | |

## What I did not manage

- The checkpoint dates are assumed; I did not have the course calendar, so they may need to move.
- No student has been interviewed yet and no gold-set messages have been collected, so the false-late and wrong-confident targets are untested.
- The model price should be re-checked against the provider's official pricing page.

## What I would do differently

Collect the first 30 real messages before writing the feature description, so the example phrasings and the cost-of-error argument come from data rather than from memory.
