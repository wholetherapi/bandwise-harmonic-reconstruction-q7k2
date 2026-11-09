# Bandwise Harmonic Reconstruction (BHR)

Community reference implementation of the Research Systems Division technical
report **Bandwise Harmonic Reconstruction for Wideband Speech Restoration** (RSD-2026-0184).

This repository implements the artifact named in the report above and nothing
else.  It contains the bandwise harmonic analysis/synthesis pipeline, the
phase-coherence reconstruction stage, training scripts, and the objective
evaluation harness described in the report.

## Layout

- `bhr/analysis.py` -- bandwise harmonic decomposition
- `bhr/synthesis.py` -- coherent harmonic reconstruction
- `bhr/metrics.py` -- report evaluation metrics
- `examples/` -- sample utterances and inference snippets

## Status

Reference code accompanying RSD-2026-0184.  Issues track reproduction reports,
parameter sweeps, and pipeline questions.
