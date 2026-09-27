# Sung Hun Kwag

**Independent AI Systems Researcher**

I study where learning systems break down under constrained compute, weak evaluators, distribution shift, and self-modification pressure. I turn those breakdown points into mechanisms for search, validation, memory, and generalization.

Failure is treated as signal, not noise. Most experiments are designed to be reproducible on CPU.

**Research site:** [Intelligence Research Project](https://sunghunkwag.github.io/) · [Recursive self-improvement: definition, history, and how to test a claim](https://sunghunkwag.github.io/research/recursive-self-improvement/)

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
