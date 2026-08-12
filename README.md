# ScreenSim gallery

A white-box phone-world engine for real-time assistance benchmarks.

**Live page:** https://hellomuffin.github.io/screensim-gallery/

- Engine architecture (deterministic backend state machine + rendered projection)
- ScreenSim vs OSWorld-2 trade-off analysis
- 16 curated long-horizon tasks with completion recordings + multi-path DAGs
- 229 auto-generated tasks derived from the mirrored Apple iPhone User Guide,
  each with a machine-verified state-diff goal and a citation to its article

The engine itself (deterministic scene-graph state, gesture grounding, iOS-18
renderer, manual mirror + coverage instrumentation) lives in the ScreenSim
repository; this repo hosts the generated gallery.
