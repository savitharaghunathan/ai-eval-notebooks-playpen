## Open questions

- How do we mitigate LLM evaluators over-favoring “LLM-like” responses?
- Can we design our prompts to explicitly reduce first case bias or style alignment bias?
- At what level of metric variability (±0.05? ±0.1?) do we consider results stable?
- How many sampling runs (`n`) do we need to average scores for reproducibility?
- Do we enforce minimum thresholds (like `faithfulness > 0.85`), and how do we decide these cutoffs?
