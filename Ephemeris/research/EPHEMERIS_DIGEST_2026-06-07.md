# EPHEMERIS DIGEST — 2026-06-07

> Auto-collected research on radio astronomy, sonification, and space data.
> Sources: arXiv, NASA, GitHub, Semantic Scholar.
> Query topics: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy.

---

## arXiv

*New entries not present in the 2026-06-06 digest.*

| # | Title | Authors | Date | Summary | Language/Tools | URL |
|---|-------|---------|------|---------|----------------|-----|
| 1 | A High-Bandwidth Backplane for Wideband Radio Interferometers and Integration with the CHORD Telescope Correlators | Wellington Avelino, Joshua Montgomery, Jean-Francois Cliche, Graeme Smecher, Matt Dobbs | 2026-06-01 | Describes a scalable FPGA backplane architecture for the CRS platform enabling high-channel-count wideband radio correlators with synchronised timing, validated against CHORD telescope requirements. | FPGA (CRS platform) | https://arxiv.org/abs/2606.02825 |
| 2 | An Attempt to Search for Unintended Electromagnetic Radiation from Starlink Satellites with the 21 Centimeter Array: Methodology and RFI Characterization | Xupiao Yang, Qijun Zhi, Yanbin Yang et al. | 2026-03-08 | Uses the 21 Centimeter Array to detect unintended electromagnetic emissions from Starlink satellites and validates the detection pipeline via ORBCOMM signal analysis, introducing the Python package `orbdemod` for satellite signal demodulation. | Python (`orbdemod`) | https://arxiv.org/abs/2603.07631 |
| 3 | The τ of Neutral Hydrogen: Increased CMB Optical Depth at Long Wavelengths | Gilbert Holder, Adrian Liu, Tzu-Ching Chang, David Zegeye | 2026-05-21 | Shows that resonant 21 cm absorption by neutral hydrogen measurably increases CMB optical depth at radio wavelengths, providing a novel handle on spin temperature and neutral fraction of cosmic gas. | — | https://arxiv.org/abs/2605.22934 |
| 4 | Simulations of the 21cm Emission Line for Upcoming Large-Scale HI Galaxy Surveys | Joël Mayor, Marta Spinelli, Gabriella De Lucia et al. | 2026-02-24 | Develops a simulation framework based on GAEA and L-Galaxies semi-analytical models to predict 21 cm neutral hydrogen emission line properties for forthcoming SKA Observatory wide-field surveys. | — | https://arxiv.org/abs/2602.21058 |
| 5 | Cost Effective Designs For Next-Generation Radio Telescopes | G B Raghavkrishna, Deeptangshu Banik, B Ravi Kumar, D Veeraswamy | 2025-06-27 | Proposes affordable engineering designs for small-scale radio telescopes that aim to achieve scientific results comparable to professional facilities through novel design optimisations. | — | https://arxiv.org/abs/2506.22398 |

---

## NASA

*No new sonification or space-audio releases identified for June 2026 in this sweep.*

> The most recent NASA sonification releases remain the February 2026 Planetary Parade (Jupiter, Saturn, Uranus — Chandra + Hubble/Cassini/Keck) and the May 2025 Black Hole Prelude/Fugue (WR 124, SS 433, Centaurus A), both catalogued in prior digests.

---

## GitHub

*New or significantly updated repositories not present in the 2026-06-06 digest.*

| # | Repository | Language | Last Updated | Summary | URL |
|---|-----------|----------|-------------|---------|-----|
| 1 | lintian233/astroflow | Python | 2026-06-04 | One-stop real-time GPU-accelerated single-pulse and Fast Radio Burst (FRB) search pipeline for radio astronomy data streams. | https://github.com/lintian233/astroflow |
| 2 | miguelcarcamov/gpuvmem | CUDA | 2026-05-19 | GPU-accelerated framework for radio astronomical image synthesis using the Maximum Entropy Method (MEM), targeting high-resolution interferometric imaging. | https://github.com/miguelcarcamov/gpuvmem |

---

## Semantic Scholar

*No new entries beyond those catalogued in the 2026-06-05 and 2026-06-06 digests (XSONIFY, Web Sonification Sandbox, Parameter Mapping Sonification, sonoUno analysis, and the STRAUSS/survey cross-listings).*

---

## Summary Statistics

| Source | New entries this digest | Notes |
|--------|------------------------|-------|
| arXiv | 5 | 4 radio astronomy / 21 cm; 1 low-cost telescope design |
| NASA | 0 | No new June 2026 sonification releases found |
| GitHub | 2 | FRB pipeline; GPU imaging |
| Semantic Scholar | 0 | No new items found |
| **Total new** | **7** | |

---

## Open Gaps / Watch List

- **JPL Horizons → audio pipeline**: Still no dedicated papers or repositories mapping Horizons ephemeris data directly to audio synthesis parameters. Closest match remains arXiv:2405.11382 (*Toward an Auditory Virtual Observatory*) and the GitHub project `sesselastronaut/celestialBodyTracking` (PyEphem + Web Audio API).
- **OSC + live telescope data**: No public 2024–2026 projects found coupling Open Sound Control directly to real telescope or ephemeris data streams.
- **RTL-SDR + direct sonification in one pipeline**: Separate ecosystems continue to advance (rtlobs, gr-radio_astro for SDR capture; STRAUSS/astronify for sonification) but no repository combining both end-to-end has been identified.
- **CHORD telescope**: New backplane paper (2606.02825) signals active hardware development; worth monitoring for associated signal-processing and data-output software repositories.

---

*Digest generated automatically on 2026-06-07. Queries run against arXiv, NASA, GitHub, and Semantic Scholar.*
