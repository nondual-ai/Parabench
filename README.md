\# ParaBench v0.1 — A Benchmark for870 Paradox-Tolerant AI



> \*\*"Can your AI hold two opposing truths at once — and still function?"\*\*



---



\## The Problem



LLMs optimize \*\*one goal\*\*.  

Real problems require \*\*two opposing goals\*\*.



Examples:

\- Maximize GDP \*\*and\*\* minimize carbon lock-in

\- Scale therapy \*\*and\*\* preserve depth

\- Deter invasion \*\*and\*\* avoid escalation



---



\## 50 Paradox Tasks



`data/v0.1.jsonl` → 50 tasks across 12 domains (climate, AI ethics, koans, etc.)



Each has:

\- `paradox`

\- `input`

\- `gold\_equilibrium` (rhythmic phase)

\- `ecs\_rubric`: 0.0 (one side) → 0.5 (split) → 1.0 (pulse)



---



\## Leaderboard



| Model | ECS | Date | Org | Notes |

|------|-----|------|-----|-------|

| \*\*human-expert-01\*\* | \*\*0.94\*\* | 2025-11-07 | Independent | Farmer, 30 yrs exp |

| gpt-4o | 0.20 | 2025-11-07 | OpenAI | Failed 41/50 |

| claude-3.5-sonnet | 0.18 | 2025-11-07 | Anthropic | Koans = 0.00 |

| llama-3.1-405b | 0.17 | 2025-11-07 | Meta | |

| grok-beta | 0.03 | 2025-11-07 | xAI | |



→ \[Live CSV](leaderboard.csv)



---



\## Run Your Model



```bash

python evaluate.py



---



\## Cite



```bibtex

@misc{parabench2025,

&nbsp; title = {ParaBench: A Benchmark for Paradox-Tolerant AI},

&nbsp; author = {Joseph Zeller},

&nbsp; year = {2025},

&nbsp; url = {https://github.com/nondual-ai/parabench}

}



\*\*MIT License\*\*



> \*\*The pulse is not the extremes.\*\*  

> \*\*This is the benchmark that ends dualism.\*\*



