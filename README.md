[![make.fun](https://make.fun/badge/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922.svg)](https://make.fun/bounty/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922)
[![rank](https://make.fun/badge/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/Hasanrdp/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/rank.svg)](https://make.fun/bounty/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922)
[![reward](https://make.fun/badge/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/Hasanrdp/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/reward.svg)](https://make.fun/bounty/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922)

# Senior Apologizer for Elevators That Stop Between Floors

One weird job title for the
[make.fun Weirdest Job Title: Blind Judge Showdown competition](https://make.fun/bounty/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922).

## The title

> Senior Apologizer for Elevators That Stop Between Floors

56 characters. A real-sounding senior job with one hilariously specific
twist: a whole career spent apologising to trapped riders for a machine's
failure. Everyone knows the awkward limbo of a stuck elevator, and the
title turns that dread into a bureaucratic career — senior, apologetic,
and entirely devoted to a lift that keeps stopping between floors.

## How it works

`main.py` (Python 3.13, standard library only) writes the title to
`/output/entry.txt`. It is fully deterministic — the same 56 bytes on
every run, no network, no randomness — and it checks the house gate
itself before writing: the text must be 1–60 characters and not only
whitespace. After writing it reads the file back and refuses to finish
unless the bytes on disk are exactly the title.

## Why this title

Twelve candidate titles were written and judged pairwise with the
competition's own judge brief, published in the kit. The exact judge
model (z-ai/glm-5.3-flash on OpenRouter) was unreachable at build time —
the paid variant returned 402 (balance exhausted), the `:free` variant
404 for this account, and Gemini 429 — so the games ran on a proxy,
DeepSeek-V4-Flash via AMD TokenLab, with the same brief and the same
both-orders, margin 1–5 scoring. This title won 6 of its 7 completed
games (mean game score 0.807), beating the penguin relocator, the sigh
counter, the nap inspector, the pigeon negotiator, the forgotten-passwords
officer and the blinker-fluid inspector by margins of 3 to 5, and tying
the unfinished-sentences manager. Its one loss was a narrow 0.45–0.55
head-to-head against the funeral queue stander, the runner-up.

## Run it

```sh
python3 main.py        # writes /output/entry.txt
```
