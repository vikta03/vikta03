# Remmy Victor

### I build chess engines that learn—and tools that let you look inside them.

My work connects **model design, training, fast inference, chess search and
visual explanation**. Two engine projects explore the same question from
different directions: how much chess understanding can fit on one laptop?

| Start here | What I built | Take a look |
|---|---|---|
| **[FORGE](https://github.com/vikta03/forge)** | CPU chess engines trained on **213.9M retained positions**. Incremental learned memory, specialist readers and a 4.80 MB Wide192 model. | [Inside the model](https://github.com/vikta03/forge/blob/main/forge-next/visuals/README.md) · [Source + weights](https://github.com/vikta03/forge/releases/tag/research-2026-10-26) |
| **[VEGAM](https://github.com/vikta03/vegam)** | A personally trained **9.8M-parameter transformer**, GPU inference and an illustrated **102-page book** following a bishop move through the network. | [Read the book](https://github.com/vikta03/vegam/releases/download/v1.0.0/inside-vegam.pdf) · [Play](https://github.com/vikta03/vegam/blob/main/docs/INSTALL.md) |
| **[Tiara](https://github.com/vikta03/tiara)** | A chess analysis interface with a trained board-recognition model and engine-analysis tools. | [Explore the project](https://github.com/vikta03/tiara) |

[![Enter FORGE's trained Specialists evaluator](https://raw.githubusercontent.com/vikta03/forge/main/forge-next/visuals/explorer/overview.png)](https://github.com/vikta03/forge/blob/main/forge-next/visuals/README.md)
*A model you can enter: the Specialists explorer shows real weights and
numerical evaluations. Its arithmetic was checked against 128 saved native
engine positions; the physical layout is an illustration.*

### More than a demo

- **Build it, train it, play it.** Model mathematics, export formats, engine
  integration and reproducible source are published alongside the weights.
- **Keep the evidence.** Controlled matches, confidence intervals, correctness
  fixtures and unsuccessful experiments are part of the work. Bigger networks
  did not always win; the [FORGE results](https://github.com/vikta03/forge/blob/main/forge-next/EVIDENCE.md) show that.
- **Contribute upstream.** Investigating VEGAM produced three Lc0 bug reports;
  [the fullmove-number report](https://github.com/LeelaChessZero/lc0/issues/2471)
  led to a [merged upstream fix](https://github.com/LeelaChessZero/lc0/pull/2480).
  Patch contributors retain their own credit.

FORGE grows from **Boring**, my earlier alpha-beta engine. VEGAM's model and
training are my work; its search foundation comes from **Leela Chess Zero**.
The repositories document those boundaries. **[MyChess2](https://github.com/vikta03/mychess2)**
remains archived as an earlier chapter.
