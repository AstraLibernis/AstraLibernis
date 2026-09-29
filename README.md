# Astra Libernis — *Freedom of the Stars*

The stars give their knowledge freely — physics, math, light — to anyone who
simply looks up. Knowledge should be the same.

Too many open projects have been bought, closed, and sold back to the people
who depended on them — sometimes tools people's safety relied on. Not these.
Everything here is copyleft and will stay that way: build on it, even charge
for your work, but you can never take it away from anyone.

Architect-led, **AI-built, never AI-trusted**. I design, direct and verify;
most of the code is written by Claude. Every result is verified, every dataset
traceable to its source, every project understood down to the machine and
closed with an honest, written conclusion. The build is the proof that the
understanding is real — then the understanding is set free.

**Focus:** Zig · portable SIMD · trustworthy measurement · grounding LLMs in
real toolchains.

---

## Projects

### Grounding LLMs in the real toolchain
Keep an AI writing *current, correct* code by checking it against ground truth,
not stale memory.

| Project | What it is | Licence | Status |
|---|---|---|---|
| [**zcanon**](https://github.com/AstraLibernis/zcanon) | Zig-competence pack for an LLM — grounds every std API call in the *installed* std and flags common LLM Zig mistakes. | GPL-3.0+ | v0.2.0 · active |
| [**zephem**](https://github.com/AstraLibernis/zephem) | A complete, self-checking map of the Zig std you actually have installed (and your project's dependencies), regenerated from the toolchain's own source. What `zcanon` checks every std call against. | GPL-3.0+ | v0.6.0 · active |

### Fast systems code in Zig
| Project | What it is | Licence | Status |
|---|---|---|---|
| [**zarbor**](https://github.com/AstraLibernis/zarbor) | Gradient-boosted trees, random forests and regularised linear models for tabular CSV, dependency-free — with cross-validation and hyperparameter search as first-class subcommands. | LGPL-3.0+ | v0.5.0 |
| [**zsift**](https://github.com/AstraLibernis/zsift) | Zero-allocation parsing of delimited/tabular text — SIMD fast path, multi-core parsing at exact record boundaries, bounded-memory streaming. CSV by default. | LGPL-3.0+ | v0.4.0 · complete |

### Upcoming
| Project | What it is | Licence | Status |
|---|---|---|---|
| **zmural** | A free live wallpaper manager for Windows and Linux — video, web and shader wallpapers that get out of the way the moment a game takes the screen. | GPL-3.0+ | In development |

---

## How I work

- **Verify everything — including the AI.** Linters, fuzzers, adversarial audits, render-and-diff. LLM output isn't trusted; neither are my own self-authored tests.
- **Traceable facts only.** No hype. Ties, caveats, and untested regimes get flagged as loudly as wins; results are tagged with the machine they ran on.
- **Archive, don't delete.** Provenance and reproducibility first — history is never overwritten or hidden.
- **Close cleanly.** A project ends with a documented conclusion the moment the understanding is proven, not when it could ship for profit.

## Licence and the commons pledge

- **Apps and tools** (zcanon, zephem, zmural) are **GPL-3.0-or-later**. Libraries (zarbor, zsift) are **LGPL-3.0-or-later**, so any program may use them, but the libraries themselves, and every change to them, stay free.
- **Commons forever.** Every project listed here will stay free software. I will not relicense them to closed terms, sell their copyright, or ask contributors to sign a CLA.
- **Contributors keep their copyright.** Contributions are accepted under the [Developer Certificate of Origin](https://developercertificate.org/) (`git commit -s`), so no single party, me included, can ever close these projects alone.
- **Earlier versions** were released under MIT, and those copies stay MIT. Everything from the licence change onward is copyleft.
- **If I ever build something to sell**, it will be a separate project that says so from day one, never a closed version of anything here.

**A note on AI authorship.** Copyright, and with it the licence, covers the human work in these projects: the design, direction, selection, arrangement and editing. Under current US Copyright Office guidance, material generated purely by a machine may not be copyrightable. Where that is the case, that material is already free for everyone.
