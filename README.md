# Astra Libernis — *Freedom of the Stars*

The stars give their knowledge freely — physics, math, light — to anyone who
simply looks up. Knowledge should be the same: never gated, never sold,
especially when it can help someone. So everything here is open, FOSS, and
built for the commons.

Architect-led, **AI-assisted but never AI-trusted**. Every result is verified,
every dataset traceable to its source, every project understood down to the
machine and closed with an honest, written conclusion. The build is the proof
that the understanding is real — then the understanding is set free.

**Focus:** Zig · portable SIMD · trustworthy measurement · grounding LLMs in
real toolchains.

---

## Projects

### Grounding LLMs in the real toolchain
Keep an AI writing *current, correct* code by checking it against ground truth,
not stale memory.

| Project | What it is | Status |
|---|---|---|
| [**zcanon**](https://github.com/AstraLibernis/zcanon) | Zig-competence pack for an LLM — grounds every std API call in the *installed* std and flags common LLM Zig mistakes. | Active |
| [**zephem**](https://github.com/AstraLibernis/zephem) | Extracts a Zig module into pristine, regenerable datasets for LLMs & static research. The map `zcanon` reads. | Active |

### Fast systems code in Zig
| Project | What it is | Status |
|---|---|---|
| [**zarbor**](https://github.com/AstraLibernis/zarbor) | Gradient-boosted trees, random forests and regularised linear models for tabular CSV, dependency-free — with cross-validation and hyperparameter search as first-class subcommands. | v0.4.0 |
| [**zsift**](https://github.com/AstraLibernis/zsift) | Zero-allocation parsing of delimited/tabular text — SIMD fast path + bounded-memory streaming. CSV by default. | v0.3.0 · complete |

---

## How I work

- **Verify everything — including the AI.** Linters, fuzzers, adversarial audits, render-and-diff. LLM output isn't trusted; neither are my own self-authored tests.
- **Traceable facts only.** No hype. Ties, caveats, and untested regimes get flagged as loudly as wins; results are tagged with the machine they ran on.
- **Archive, don't delete.** Provenance and reproducibility first — history is never overwritten or hidden.
- **Close cleanly.** A project ends with a documented conclusion the moment the understanding is proven, not when it could ship for profit.

## License

MIT unless a repository states otherwise — free to use, modify, and build upon.
