# Sung Hun Kwag

**Independent AI Systems Researcher**

I study where learning systems break down under constrained compute, weak evaluators, distribution shift, and self-modification pressure. I turn those breakdown points into mechanisms for search, validation, memory, and generalization.

Failure is treated as signal, not noise. Most experiments are designed to be reproducible on CPU.

## Open questions

**RSI stability**
Can self-improvement loops remain stable under non-leaking episodic memory, rollback constraints, and validation-only gates?

Related repositories: [rsi-metaforge-core](https://github.com/sunghunkwag/rsi-metaforge-core), [self-improving-research-kernel](https://github.com/sunghunkwag/self-improving-research-kernel), [DeepNeural-AutoExploration](https://github.com/sunghunkwag/DeepNeural-AutoExploration)

**Attention-free sequence modeling**
Can long-range dependencies be handled without attention, softmax, or transformer-style assumptions?

Related repositories: [attention-free-sequence-model](https://github.com/sunghunkwag/attention-free-sequence-model), [RSI-NAS-Attention-Free](https://github.com/sunghunkwag/RSI-NAS-Attention-Free), [DHC-SSM-Enhanced](https://github.com/sunghunkwag/DHC-SSM-Enhanced), [SSM-MetaRL-TestCompute](https://github.com/sunghunkwag/SSM-MetaRL-TestCompute)

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

## Contact

[sunghunkwag@gmail.com](mailto:sunghunkwag@gmail.com)
