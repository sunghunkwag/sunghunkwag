# Sunghun Kwag — Independent AI Systems Researcher

I build experimental AI systems that test the boundary conditions of machine intelligence: recursive self-improvement, alternative sequence architectures, verification-first evaluation, and compute-efficient learning under constrained resources.

My work is not centered on application-layer AI wrappers. It is focused on the machinery underneath: architectures, benchmarks, failure modes, self-modification loops, and evaluation protocols that expose whether an AI system is genuinely improving or merely optimizing surface metrics.

## Research Program

### Hybrid Program Synthesis with Safe Self-Improvement Loops

I work on experimental systems capable of synthesizing, testing, abstracting, and reusing code under controlled safety constraints.

- **Hybrid Program Synthesis with RSI** — an experimental synthesis engine using neuro-genetic search, hierarchical library learning, persistent primitive discovery, and watchdog process isolation.
- Focuses on safe execution of generated programs, semantic uniqueness checks, reusable primitive abstraction, and meta-learning over synthesis success patterns.
- Designed as a research platform for studying constrained recursive improvement and autonomous operator discovery.

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

- Recursive and self-modifying AI systems
- Verification-first evaluation and stability analysis
- Architecture search beyond conventional Transformer scaling
- State-space and attention-free sequence modeling
- Failure-driven research: documenting where systems break, not only where they work
- Compute-efficient experimentation under real-world constraints
- Safety boundaries, sandboxing, and adversarial evaluation protocols

## Research Style

I treat AI systems as structures to be stress-tested, not products to be polished.

My repositories are built around a recurring question:

> Can adaptive AI systems reorganize and improve themselves while remaining measurable, inspectable, and constrained by explicit verification procedures?

This question drives my work across program synthesis, alternative architectures, state-space modeling, recursive adaptation, and failure analysis.

## Selected Repositories

- [Hybrid-Program-Synthesis-with-RSI](https://github.com/sunghunkwag/Hybrid-Program-Synthesis-with-RSI) — safe self-improving program synthesis engine
- [attention-free-sequence-model](https://github.com/sunghunkwag/attention-free-sequence-model) — attention-free architecture search and sequence modeling experiments
- [SSM-MetaRL-TestCompute](https://github.com/sunghunkwag/SSM-MetaRL-TestCompute) — SSM adaptation, switching dynamics, and constrained-compute testing
- [DHC-SSM-Enhanced](https://github.com/sunghunkwag/DHC-SSM-Enhanced) — deterministic hierarchical causal SSM experiments
- [MetaRL-Agent-Framework](https://github.com/sunghunkwag/MetaRL-Agent-Framework) — meta-reinforcement learning agent framework
- [Neural-Symbolic-Reasoning-Framework](https://github.com/sunghunkwag/Neural-Symbolic-Reasoning-Framework) — neural-symbolic reasoning experiments
- [structural-memory-field](https://github.com/sunghunkwag/structural-memory-field) — structural memory and latent residue experiments

## Contact

Email: [sunghunkwag@gmail.com](mailto:sunghunkwag@gmail.com)  
Intro Video: https://www.youtube.com/watch?v=Ky7TQA2BUnk
