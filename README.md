# Portfolio Bet Prioritizer

An interactive weighted-scoring tool for early-R&D portfolio trade-offs: set leadership's priorities, watch the ranking move, and see exactly which weight change would flip the #1 pick.

**[Live demo](https://portfolio-bet-prioritizer.vercel.app)** — works immediately, no API key or setup required. Everything runs in your browser; nothing you enter is stored or sent anywhere. Please use fictional/sample data only.

## Who it's for

Portfolio strategy, R&D leadership, and program leads who need a ranking people trust rather than argue with.

## Why it matters

R&D leadership teams decide where the next discovery dollar goes under competing priorities, and the debate often turns into 'my program vs. yours' instead of 'what are we optimizing for?' This tool makes the trade-off explicit and shows how fragile the #1 pick is, so leadership agrees on priorities before arguing about programs.

## What it does

- Choose a leadership lens (patient-impact first, capital-efficient, differentiation-led) or set weights yourself
- See the live ranking and the biggest driver behind each bet's score
- Get a robustness verdict — fragile, moderate, or robust — and the exact weight change that would flip the leader
- Edit any 0–10 score to test how much one contested judgement moves the outcome

## Product decisions that mattered more than the model

1. **Agree weights before rankings** — the conversation moves to priorities, not programs
2. **Robustness as an output** — not just who's #1, but how sure we should be
3. **Fully inspectable** — no model in the loop

## Built with

- HTML, CSS, JavaScript (single-file prototype, no framework, no build step)

## Run locally

Open `index.html` in any browser — no install needed.

## Status

This is a prototype built to explore a problem space, using fictional/synthetic data — not a finished product and not connected to any organization's real systems. Built by [Jane Natividad](https://github.com/jane-natividad) — see more at [jane-natividad.github.io](https://jane-natividad.github.io).
