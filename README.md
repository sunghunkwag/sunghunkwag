# Sung Hun Kwag

**Independent AI Systems Researcher**

I study where learning systems break down under constrained compute, weak evaluators, distribution shift, and self-modification pressure. I turn those breakdown points into mechanisms for search, validation, memory, and generalization.

Failure is treated as signal, not noise. Most experiments are designed to be reproducible on CPU.

**Research site:** [Intelligence Research Project](https://sunghunkwag.github.io/) · [Recursive self-improvement: definition, history, and how to test a claim](https://sunghunkwag.github.io/research/recursive-self-improvement/)

## Auditing self-improving AI systems

When a self-improving system also writes or selects the test that admits its changes, a gain can pass without being real. In June 2026 I filed 27 issues in 23 open-source self-improving AI projects looking for exactly that: an optimizer that never touched its target, a selection mode that kept the worst candidates, a mean-score gate that accepted evaluator gaming while a task regressed, held-out answers leaking into search.

- [NousResearch/hermes-agent-self-evolution#141](https://github.com/NousResearch/hermes-agent-self-evolution/issues/141): skill evolution was a no-op; reproduced independently by two other users
- [microsoft/SkillOpt#67](https://github.com/microsoft/SkillOpt/issues/67): another user reported a reproducible case of the gate accepting an evaluator-gaming edit (mean 0.682 → 0.852 while one task regressed)
- [iLearn-Lab/EvoHarness#1](https://github.com/iLearn-Lab/EvoHarness/issues/1): negative-control probes implemented by a repository collaborator
- [gepa-ai/gepa#381](https://github.com/gepa-ai/gepa/issues/381): admission ledger implemented by an external contributor ([PR #382](https://github.com/gepa-ai/gepa/pull/382), open)
- [jennyzzt/dgm#31](https://github.com/jennyzzt/dgm/issues/31): Darwin Gödel Machine "best" selection fix opened by another contributor ([PR #32](https://github.com/jennyzzt/dgm/pull/32), open)

Full record, failure patterns and limits: [sunghunkwag.github.io/research/self-improvement-audits](https://sunghunkwag.github.io/research/self-improvement-audits/). An issue is a report, not a confirmed defect; most are still open.

## Open questions

**Recursive self-improvement, measured**
Does a self-improvement loop beat a matched control that is denied the mechanism, at equal compute, on held-out tasks, with identical random streams?

Related repository: [gated-self-improvement](https://github.com/sunghunkwag/gated-self-improvement)

**RSI stability**
Can self-improvement loops remain stable under non-leaking episodic memory, rollback constraints, and validation-only gates?

Related repositories: [rsi-metaforge-core](https://github.com/sunghunkwag/rsi-metaforge-core), [self-improving-research-kernel](https://github.com/sunghunkwag/self-improving-research-kernel), [DeepNeural-AutoExploration](https://github.com/sunghunkwag/DeepNeural-AutoExploration)

**Parameter-free structure**
Can representation and memory be built without neural networks, learned weights, or standard gradient-based training?

Related repositories: [field-interference-network](https://github.com/sunghunkwag/field-interference-network), [structural-memory-field](https://github.com/sunghunkwag/structural-memory-field), [OMEGA-THDSE](https://github.com/sunghunkwag/OMEGA-THDSE)

**Measuring self-improvement**
Which axes matter for evaluating self-improvement: self-modification depth, operator discovery, meta-adaptation, rollback stability, evaluator robustness, and failure containment?

Related repository: [rsi-bench](https://github.com/sunghunkwag/rsi-bench)

## Evaluation discipline

Experiments use sealed or hidden evaluations where possible, validation-gated synthesis, rollback constraints, evaluator evolution, and failure-to-rule compression.

Benchmark leakage and evaluator gaming are treated as default threats, not afterthoughts.

Only changes that pass validation are kept. Failed changes remain as records.

## Support

Support goes to research funding: the compute and time the next experiments need. There is no fixed target, and any amount helps. [GitHub Sponsors](https://github.com/sponsors/sunghunkwag) takes monthly or one-time support, or write by email.

## Contact

[sunghunkwag@gmail.com](mailto:sunghunkwag@gmail.com)
