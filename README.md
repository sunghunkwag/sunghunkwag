# Sunghun Kwag — Independent AI Systems Researcher

I build experimental AI systems that test the boundary conditions of machine intelligence: recursive self-improvement, alternative sequence architectures, verification-first evaluation, and compute-efficient learning under constrained resources.

My work is not centered on application-layer AI wrappers. It is focused on the machinery underneath: architectures, benchmarks, failure modes, self-modification loops, and evaluation protocols that expose whether an AI system is genuinely improving or merely optimizing surface metrics.

## Research Program

### Recursive Self-Improvement & AI Verification

I am developing practical infrastructure for evaluating Recursive Self-Improvement (RSI) as a measurable systems property rather than a speculative concept.

- **RSI-Bench** — a multi-axis benchmark for evaluating self-modifying AI systems across modification depth, improvement trajectory quality, operator discovery, meta-adaptation speed, safety/stability, and autonomous goal generation.
- Includes statistical evaluation, bootstrap confidence intervals, Pareto analysis, convergence detection, safety boundary checks, and a tested implementation suite.
- Goal: distinguish genuine self-improvement from metric gaming, brittle local optimization, or hidden instability.

Repository: [rsi-bench](https://github.com/sunghunkwag/rsi-bench)

### Hybrid Program Synthesis with Safe RSI Loops

I also work on RSI from the implementation side: systems that synthesize, test, abstract, and reuse code under controlled safety constraints.

- **Hybrid Program Synthesis with RSI** — an experimental synthesis engine using neuro-genetic search, hierarchical library learning, persistent primitive discovery, and watchdog process isolation.
- Focuses on safe execution of generated programs, semantic uniqueness checks, reusable primitive abstraction, and meta-learning over synthesis success patterns.

Repository: [Hybrid-Program-Synthesis-with-RSI](https://github.com/sunghunkwag/Hybrid-Program-Synthesis-with-RSI)

### Alternative Sequence Architectures Beyond Attention

A major part of my work explores whether long-range sequence modeling can be achieved without standard Transformer attention.

- **Attention-Free Sequence Model** — documents a systematic architecture search over attention-free sequence mechanisms.
- Includes manually designed failures, a successful attention-free design, and an automated search over thousands of candidate architectures.
- The project emphasizes mechanism discovery, failure documentation, long-range information transfer, hierarchical computation, and non-quadratic routing alternatives.

Repository: [attention-free-sequence-model](https://github.com/sunghunkwag/attention-free-sequence-model)

### State Space Models, Meta-Adaptation, and Stability Testing

I test state-space and post-Transformer architectures under distribution shift, constrained compute, and stability-sensitive settings.

- **SSM-MetaRL-TestCompute** — experiments with State Space Models under switching dynamics, test-time adaptation, and meta-learning scaffolds.
- Includes Switching LDS benchmarks, shock/recovery metrics, C-MAPSS Remaining Useful Life prediction, numerical stability controls, and cautious single-run benchmark reporting.

Repository: [SSM-MetaRL-TestCompute](https://github.com/sunghunkwag/SSM-MetaRL-TestCompute)

- **DHC-SSM-Enhanced** — an experimental Deterministic Hierarchical Causal State Space Model for probing linear-complexity spatial-temporal processing and RL control tasks.
- Explicitly documents not only positive learning behavior, but also numerical instability, causal leakage risks, initialization sensitivity, and scope limitations.

Repository: [DHC-SSM-Enhanced](https://github.com/sunghunkwag/DHC-SSM-Enhanced)

## Core Themes

- Recursive self-improvement as an experimentally measurable capability
- Verification-first evaluation for self-modifying systems
- Architecture search beyond conventional Transformer scaling
- State-space and attention-free sequence modeling
- Failure-driven research: documenting where systems break, not only where they work
- Compute-efficient experimentation under real-world constraints
- Safety boundaries, sandboxing, and adversarial evaluation protocols

## Research Style

I treat AI systems as structures to be stress-tested, not products to be polished.

The central question behind my repositories is:

> Can we build systems that improve, adapt, and reorganize themselves while remaining measurable, inspectable, and bounded by explicit verification protocols?

That question drives my work across RSI benchmarking, program synthesis, alternative architectures, state-space modeling, and failure analysis.

## Selected Repositories

- [rsi-bench](https://github.com/sunghunkwag/rsi-bench) — multi-axis RSI benchmark and statistical evaluation framework
- [Hybrid-Program-Synthesis-with-RSI](https://github.com/sunghunkwag/Hybrid-Program-Synthesis-with-RSI) — safe RSI-oriented program synthesis engine
- [attention-free-sequence-model](https://github.com/sunghunkwag/attention-free-sequence-model) — attention-free architecture search and sequence modeling experiments
- [SSM-MetaRL-TestCompute](https://github.com/sunghunkwag/SSM-MetaRL-TestCompute) — SSM adaptation, switching dynamics, and constrained-compute testing
- [DHC-SSM-Enhanced](https://github.com/sunghunkwag/DHC-SSM-Enhanced) — deterministic hierarchical causal SSM experiments
- [MetaRL-Agent-Framework](https://github.com/sunghunkwag/MetaRL-Agent-Framework) — meta-reinforcement learning agent framework
- [Neural-Symbolic-Reasoning-Framework](https://github.com/sunghunkwag/Neural-Symbolic-Reasoning-Framework) — neural-symbolic reasoning experiments
- [structural-memory-field](https://github.com/sunghunkwag/structural-memory-field) — structural memory and latent residue experiments

## Contact

Email: [sunghunkwag@gmail.com](mailto:sunghunkwag@gmail.com)  
Intro Video: https://www.youtube.com/watch?v=Ky7TQA2BUnk
