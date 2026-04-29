# RL for LLMs — Class Presentation

A Beamer slide deck I prepared for my Advanced Machine Learning class on **reinforcement learning techniques for large language models** — covering the lineage from REINFORCE to PPO to GRPO, and what RLHF / RLAIF actually optimize.

Part of my Advanced Machine Learning class portfolio (Ransom Everglades, 2025–26).

## Topics covered

- Why RL? (the supervised-learning gap for open-ended generation)
- Policy gradient basics — REINFORCE, baselines, advantage
- PPO — clipped surrogate objective, why it stabilizes training
- GRPO — group-relative advantage, no value model
- RLHF pipeline — reward model from human preferences → policy optimization
- Recent shifts — RLAIF, verifier-based RL on math/code

## Files

- `rl_for_llms_presentation.tex` — Beamer source
- `rl_for_llms_presentation.pdf` — rendered slides

## Build

```bash
pdflatex rl_for_llms_presentation.tex
```
