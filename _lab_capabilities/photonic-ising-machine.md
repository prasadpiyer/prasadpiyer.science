---
title: "Photonic Ising Machine"
slug: photonic-ising-machine
date: 2025-08-16
images:
  - Lab/Photonic_Ising.png
summary: "Photonic Ising machine for combinatorial optimization"
---

Liquid-crystal spatial light modulators (LC-SLMs) and Fourier-optical relays enable electronically programmable phase lattices for large-scale spin encoding and optical energy evaluation. Building on our free-space 4f platforms—phase-only modulation, stable polarization conditioning, and high dynamic-range far-field metrology—we implement a compact photonic Ising machine (PIM) that supports binary or multi-level phase spins, programmable input amplitudes, and precise Fourier-plane detection.

## Experimental Capabilities

Our spin layer uses a reflective, phase-only Meadowlark LC-SLM with crossed polarimetric conditioning to suppress amplitude modulation. A precision rectangular aperture defines an L×L spin grid with uniform telecentric illumination ensuring one-to-one pixel-to-spatial frequency mapping. The module supports binary {0,π} phase encoding for Ising spins and multi-level quantization for extended state representations. An optional amplitude-shaping setup (with another phase-only SLM inteferring with mirror) upstream of the SLM imprints spatial weight vectors {J_ij} on the incident field, enabling Mattis-type coupling templates and engineered interaction kernels. A diffraction-limited 4f relay images the modulated wavefront to the Fourier plane where spin-dependent intensity distributions form. Scientific cameras (CCD/sCMOS) perform detection with software macro-pixel binning (m×m native pixels) yielding Mₓ×Mᵧ measurement grids. The system achieves >60 dB dynamic range through flat-fielding, dark subtraction, and exposure bracketing, with frame-accurate synchronization during parameter sweeps.


