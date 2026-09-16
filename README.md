# Agentic Capstone Evidence Toolkit

> A practical template and evaluation framework for presenting an agentic capstone project with clear, verifiable evidence.

## What this repository is

This is an **academic support toolkit**, not a production application or a submitted capstone product. It helps learners package a project for Demo Day in a consistent way: explain the product, map it to an evaluation rubric, and include proof that the important behaviours actually work.

## Included resources

- [`CAPSTONE-PROPOSAL-TEMPLATE.md`](CAPSTONE-PROPOSAL-TEMPLATE.md) — a guided proposal format aligned with the evaluation criteria.
- `submissions/` — the place for each project's proposal and supporting evidence.
- An evidence-first scoring model for reviewing agentic projects fairly and transparently.

## How to use it

1. Copy the proposal template into `submissions/<your-project>/proposal.md`.
2. Describe the problem, intended users, workflow, controls, and technical choices.
3. Add compact, meaningful evidence: a runnable test, reproducible run, public repository, demo, or sample output.
4. Submit the folder according to the course process.

## Evaluation framework

| Dimension | Weight | What reviewers look for |
|---|---:|---|
| Agentic depth | 25 | A real plan → act → observe loop, appropriate tools, autonomy, or memory — not only a prompt wrapper |
| Engineering excellence | 20 | Reliable implementation, tests, error handling, and observability |
| Product and usability | 15 | A clear user problem and an experience people can use |
| Potential and defensibility | 15 | A credible path to a differentiated, useful product |
| Safety and control | 15 | Human oversight, limits, trustworthy input handling, and safe handling of secrets |
| Complexity and difficulty | 5 | A genuinely difficult problem solved well |
| Demo and communication | 5 | Clear explanation plus evidence that the project runs |

Scores are assigned from 1–10 per dimension, for a weighted total out of 100.

## Evidence standard

The framework distinguishes between claims and proof:

- **Asserted:** described only in prose.
- **Present:** implemented code or an artifact is included.
- **Demonstrated:** a reviewer can verify the behaviour through a test, reproducible run, or live demo.

Strong submissions curate a small set of high-signal artifacts rather than relying on screenshots or broad claims.

## Safety expectations

Agentic systems should keep humans in control of high-impact actions, set sensible limits, treat untrusted input carefully, and avoid exposing secrets. Safety is evaluated as a core design property, not an optional extra.

## Scope

Use this repository as a reusable course or mentoring resource. A learner's actual project and evidence should live in its own submission folder or public repository.
