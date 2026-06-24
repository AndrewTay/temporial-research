# Temporial Research — SIGGRAPH × CVPR 2026 pipeline scan

A scan of 2026 SIGGRAPH/CVPR papers across the three stages of the Ani3D reskin pipeline —
**making production-ready 3D models**, **animating them**, and **retargeting mocap** — with the
top 3 picks per stage, then every paper with open code that fits a single 16 GB GPU **built and
tested live on a cat & pug**.

**Live:** https://andtay.com/temporial-research/

## What's inside
- **Built & tested (interactive 3D + media):**
  - *TokenRig / Skin Tokens* (SIGGRAPH 2026) — auto-rigged cat (27 joints) & pug (28 joints).
  - *AnyTop* (SIGGRAPH 2025) — generated Cat & Puppy quadruped motion (MP4 + animated skeleton).
- **Flagged** (code/weights/toolchain/platform gaps): MatLat, Rigel3D, SATO, RigMo, OmniZoo,
  MoCapAnything, ViPS, 4D-Animal, SPRig, **MORPHOS**, **TRELLIS** — see the decision matrix.

## Notes
- Static site (no build step). `model-viewer` is vendored; 3D assets are draco-compressed GLBs.
- MatLat's result clips are the **authors' own media** and are linked to the
  [MatLat project page](https://matlat-proj.github.io/) rather than rehosted here.
- Hosted as a GitHub Pages project site under the apex `andtay.com` domain (no per-repo CNAME).

🤖 Generated with [Claude Code](https://claude.com/claude-code)
