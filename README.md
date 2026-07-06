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
| [**zcanon**](https://codeberg.org/AstraLibernis/zcanon) | Zig-competence pack for an LLM — grounds every std API call in the *installed* std and flags common LLM Zig mistakes. | Active |
| [**nucanon**](https://codeberg.org/AstraLibernis/nucanon) | The Nushell sibling — a self-maintaining map of nu's command surface (from live `scope commands`) + grounding skill & edit-time hook. | Active |
| [**zephem**](https://codeberg.org/AstraLibernis/zephem) | Extracts a Zig module into pristine, regenerable datasets for LLMs & static research. The map `zcanon` reads. | Active |

### Fast systems code in Zig
| Project | What it is | Status |
|---|---|---|
| [**zsift**](https://codeberg.org/AstraLibernis/zsift) | Zero-allocation parsing of delimited/tabular text — SIMD fast path + bounded-memory streaming. CSV by default. | v0.1.0 |
| [**zimd**](https://codeberg.org/AstraLibernis/zimd) | Portable SIMD ops Zig has no builtin for — gather, scatter, compress, expand, masked load/store — hardware fast path + comptime scalar fallback. | Stable |

### Trustworthy measurement & tooling
| Project | What it is | Status |
|---|---|---|
| [**benchfence**](https://codeberg.org/AstraLibernis/benchfence) | Trustworthy CPU benchmarks on noisy/shared machines (VMs, CI): detect the venue, fence the noise, gate every sample against the pinned core's idle floor. | Stable |
| [**zonar**](https://codeberg.org/AstraLibernis/zonar) | A local *"zig outdated"* — check `build.zig.zon` deps for newer versions & Zig compatibility. Zero dependencies, any git host. | Stable |
| [**gron-rs**](https://codeberg.org/AstraLibernis/gron-rs) | Rust port of `gron` — turn JSON into discrete, greppable assignments. | Stable |

### Explorations — concluded
Understanding proven and documented; closed cleanly rather than polished forever.

| Project | What it is | Status |
|---|---|---|
| [**portable-simd-crosslang**](https://codeberg.org/AstraLibernis/portable-simd-crosslang) | Portable SIMD vectors across five languages (Zig, Rust, C, Go, NumPy): benchmark harness + machine-code analysis on Zen 5 / AVX-512. | Concluded |
| [**chacha20-zig**](https://codeberg.org/AstraLibernis/chacha20-zig) | Vectorized ChaCha20 (RFC 8439) in pure Zig `@Vector` SIMD — benchmarked against stdlib, RustCrypto, Go, C, and OpenSSL asm. | Concluded |

---

## How I work

- **Verify everything — including the AI.** Linters, fuzzers, adversarial audits, render-and-diff. LLM output isn't trusted; neither are my own self-authored tests.
- **Traceable facts only.** No hype. Ties, caveats, and untested regimes get flagged as loudly as wins; results are tagged with the machine they ran on.
- **Archive, don't delete.** Provenance and reproducibility first — history is never overwritten or hidden.
- **Close cleanly.** A project ends with a documented conclusion the moment the understanding is proven, not when it could ship for profit.

## License

MIT unless a repository states otherwise — free to use, modify, and build upon.
