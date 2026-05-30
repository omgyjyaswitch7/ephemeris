# EPHEMERIS DIGEST — 2026-05-30

**Topics searched:** sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy

**Sources:** arXiv · NASA / Chandra / JPL · GitHub · Semantic Scholar

**Deduplicated against:** EPHEMERIS_DIGEST_2026-05-29.md — only new items are recorded below.

**New items this run:** 2 arXiv papers · 0 NASA items · 12 GitHub repositories · 0 Semantic Scholar-unique papers

---

## arXiv

### New Papers (not in 2026-05-29 digest)

| Title | URL | Date | Summary | Language |
|-------|-----|------|---------|----------|
| What does the Universe sound like? | https://arxiv.org/abs/2603.29996 | 2026-03-31 | Francesco Iacovelli computes the aggregate gravitational-wave audio of ~10⁶ synthetic compact binary coalescence events to produce the Universe's average sound. | — |
| Enabling Blind and Visually Impaired Individuals to Pursue Careers in Science | https://arxiv.org/abs/2511.17620 | 2025-11-18 | Petitdemange & Nashed survey barriers facing BVI scientists and propose assistive-technology and inclusive-outreach pathways, including sonification, to enable STEM careers. | — |

> **Note on arXiv:2603.29996:** The paper is tagged as an April 1, 2026 submission and carries a lighthearted framing ("perfect for sleeping"), but the gravitational-wave signal synthesis methodology is scientifically grounded.

---

## NASA / Chandra / JPL

No new NASA items found in this run. All known releases are catalogued in EPHEMERIS_DIGEST_2026-05-29.md.

---

## GitHub

### New Repositories — Radio Astronomy & SDR (active, not in 2026-05-29 digest)

| Repository | URL | Last Updated | Language | Summary |
|-----------|-----|-------------|----------|---------|
| lintian233/astroflow | https://github.com/lintian233/astroflow | 2026-05-30 | Python | Real-time GPU-accelerated single-pulse and FRB search pipeline for radio astronomy data. |
| RadioAstronomySoftwareGroup/pyuvdata | https://github.com/RadioAstronomySoftwareGroup/pyuvdata | 2026-05-28 | Python | Pythonic interface for reading, writing, and manipulating radio astronomy interferometry data across standard formats. |
| Pi-Radio-Telescope/indi-rpi-radiotelescope | https://github.com/Pi-Radio-Telescope/indi-rpi-radiotelescope | 2025-05-28 | C++ | INDI-based driver and control system for a Raspberry Pi–powered amateur radio telescope. |
| Pi-Radio-Telescope/RTData | https://github.com/Pi-Radio-Telescope/RTData | 2025-05-23 | C++ | Lightweight data visualization tool for real-time radio telescope observation output. |
| indilib/indi-3rdparty | https://github.com/indilib/indi-3rdparty | 2026-05-23 | C++ | Third-party INDI hardware driver repository covering a wide range of telescopes, SDRs, and astronomy instruments. |
| miguelcarcamov/gpuvmem | https://github.com/miguelcarcamov/gpuvmem | 2026-05-19 | CUDA / C++ | GPU-accelerated framework for radio astronomical image synthesis using maximum entropy methods. |
| MWATelescope/mwa_hyperdrive | https://github.com/MWATelescope/mwa_hyperdrive | 2026-05-21 | Rust | Calibration software for the Murchison Widefield Array (MWA) radio telescope, designed for large-scale interferometric processing. |
| spectregrams/spectre | https://github.com/spectregrams/spectre | 2026-05-16 | Python | SDR-agnostic program for capturing radio signals and generating spectrogram waterfall displays. |
| AstroAccelerateOrg/astro-accelerate | https://github.com/AstroAccelerateOrg/astro-accelerate | 2026-04-24 | C++ / CUDA | Many-core accelerated software package for time-domain radio astronomy data processing at scale. |
| tedcline/ezRA | https://github.com/tedcline/ezRA | 2025-08-17 | Python | Easy Radio Astronomy: beginner-friendly Python toolkit for SDR-based radio astronomy observations. |
| iliaplatone/OpenVLBI | https://github.com/iliaplatone/OpenVLBI | 2025-11-20 | C | Open-source library and application suite for very long baseline interferometry (VLBI) in amateur and professional astronomy. |

### New Repositories — Astronomy Sonification

| Repository | URL | Last Updated | Language | Summary |
|-----------|-----|-------------|----------|---------|
| saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool | https://github.com/saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool | 2026-04-16 | HTML / JavaScript | Interactive galaxy-field viewer and sonification instrument for SDSS DR8 / MPA-JHU astronomical catalogue data. |

---

## Semantic Scholar

No new Semantic Scholar-unique papers found in this run. Previously indexed papers are catalogued in EPHEMERIS_DIGEST_2026-05-29.md.

---

## Research Gaps (carried forward, still unresolved)

- **JPL Horizons + audio mapping:** No dedicated tools or papers combine JPL Horizons ephemeris data with direct OSC/audio output. Closest work: `AudiblePlanets` (GitHub), `HORIZONS.jl` / `lhorizon` (API clients), arXiv:2405.11382 (FITS2OSC pipeline).
- **OSC + real-time astronomy:** OSC appears only as infrastructure in broader pipelines; no paper explicitly demonstrates an OSC-driven astronomy data stream from a live telescope feed.
- **RTL-SDR + real-time sonification:** No project captures RTL-SDR radio data and routes it to a live sonification engine simultaneously — the two tool families remain separate ecosystems.
- **Celestial mechanics → audio synthesis:** `AudiblePlanets` (gregrecco67) remains the only known project mapping live orbital geometry directly to FM synthesis parameters.
