### Kartik G Bhat

PhD, UC Berkeley · MS Data Science, UT Austin · 9 years at Intel · Founding Scientist, MightyAI

I run controlled experiments on **the gap between a target and the proxy we optimize or
measure** — in reward models, judges, benchmarks, RL environments, and monitors.

---

#### Preprints (2026)

**[Synthetic Oracle Benchmark for LLM Reasoning Scaffolding](https://zenodo.org/records/19666413)** · [code](https://github.com/kar-ganap/synthoracle)
A contamination-free synthetic oracle separates reasoning quality from optimization outcome.
Structured reasoning helps weaker models (+26%) and *hurts* the strongest (−35%, p=0.0006) —
traced to context-cementing, isolated by a one-flag ablation.

**[Labels Not Loss: Multi-Stakeholder Preference Learning and Identifiability](https://zenodo.org/records/19666774)** · [code](https://github.com/kar-ganap/x-algorithm-enhancements)
A directional Goodhart condition: the cosine of trained reward-vector weights determines
whether more data helps or harms hidden stakeholders (32/32). Validated on MovieLens-100K/1M,
MIND, and Amazon Kindle.

**[Same Question, Different Answer: Latent Quality Under Critical Engagement](https://zenodo.org/records/20263194)** · [code](https://github.com/kar-ganap/crit-thinking)
A two-mode dissociation: error/gap critique drives epistemic calibration (d=1.51), reframing
critique drives analytical novelty (d=2.54). Pre-registered 14-move taxonomy; a within-condition
ablation falsified the simpler one-dial account.

**[Agent Teams vs Hub-and-Spoke Subagents](https://zenodo.org/records/19360429)** · [code](https://github.com/kar-ganap/ate-series)
Three experiments, 160 runs. Two ceiling nulls earned the third design; information asymmetry is
the structural condition that separates collaboration from parallelism (d=+1.04, p=0.011).

---

#### In flight

**[assay](https://github.com/kar-ganap/assay)** — does an RL environment teach the skill, or teach
the exploit? A zero-GPU-hour diagnostic battery for RL environments, validated against real GRPO
training outcomes.

#### Completed studies — writeups in preparation

**canary** — recursive self-training collapse. Fluent diversity collapse below 12.5% synthetic
data; cross-family replication on OLMo failed, and two of four hypotheses were withdrawn.

**[originality](https://github.com/kar-ganap/originality)** — a 24M-paper measurement study. The
*sign* of the headline effect turns out to be embedding-determined; the original mechanism claim
was withdrawn rather than reported from the one favorable embedding family.

**[polyphony](https://github.com/kar-ganap/polyphony)** — does shared context homogenize
multi-agent LLM output? The premise was refuted. The refutation, plus four self-caught
corrections, is the artifact.

---

House rules across these repos: pre-register before running · report nulls as nulls · every
number regenerates from a committed script · spend logged per run.

[LinkedIn](https://linkedin.com/in/kartikganapathi/) · gkartik@gmail.com
