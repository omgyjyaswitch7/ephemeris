# EPHEMERIS DIGEST — 2026-06-10

> Auto-collected research on radio astronomy, sonification, and space data.
> Sources: arXiv, NASA, GitHub, Semantic Scholar.
> Query topics: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy.

---

## arXiv

*New entries not present in the 2026-06-09 digest.*

| # | Title | Authors | Date | Summary | Language/Tools | URL |
|---|-------|---------|------|---------|----------------|-----|
| 1 | herakoi: a sonification experiment for astronomical data | Michele Ginolfi, Luca Di Mascolo, Anita Zanella | 2024-12-12 | Open-source ML tool converts astronomical images to sound by tracking hand movements via webcam and mapping visual properties (brightness, colour) to audio parameters, designed for research accessibility and outreach. | Python (ML, hand tracking) | https://arxiv.org/abs/2412.09152 |
| 2 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | Gustavo Magallanes-Guijón, Sergio Mendoza | 2025-02-04 | Applies MIDI and Parameter Mapping Sonification (PMSon) to multifrequency light curves of nine blazars, showing that auditory representations expose temporal variability patterns complementary to spectrograms and images. | Python, MIDI | https://arxiv.org/abs/2502.01929 |
| 3 | STRAUSS: Sonification Tools & Resources for Analysis Using Sound Synthesis (JOSS publication) | James W. Trayford et al. | 2025-04 | JOSS peer-reviewed publication formalising STRAUSS as a Python package for flexible scientific data sonification across education, communication, and technical analysis; earlier preprint (arXiv:2311.16847) was in the 2026-06-09 digest. | Python | https://arxiv.org/abs/2504.01660 |
| 4 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Diaz-Merced, Beatriz García | 2024-02-01 | Presents sonoUno software for converting astronomical CSV/spectral datasets into sound and evaluates its accessibility against ISO 9241-171 standards with visually impaired scientists. | Python (sonoUno) | https://arxiv.org/abs/2402.00611 |
| 5 | Astronomical images sonification: inclusion or outreach? | Johanna Casado, Beatriz García | 2024-02-01 | Examines whether astronomical image sonification serves scientific inclusion for visually impaired researchers or public outreach, arguing for a dual-purpose design framework. | — | https://arxiv.org/abs/2402.00952 |
| 6 | A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response | Kimberly K. Arcand, Jessica S. Schonhut-Stasik, Sarah G. Kane et al. | 2024-03-13 | Evaluates responses of blind, low-vision, and sighted participants to NASA telescope sonifications, finding significant learning gains and strongly positive engagement across all groups. | — | https://arxiv.org/abs/2403.18082 |
| 7 | Sound training platform applied to astronomy | Natasha Bertaina Lucero, Johanna Casado, Beatriz García, Gonzalo Cayo | 2024-05-09 | Introduces an e-learning platform where astronomers train data-analysis skills through structured sonification exercises, broadening participation in space science beyond visual data displays. | — | https://arxiv.org/abs/2405.06042 |

---

## NASA

*Status: No new releases confirmed beyond those catalogued in prior digests.*

> Previously catalogued releases include: **February 2026** Planetary Parade (Jupiter, Saturn, Uranus — Chandra/Hubble/Keck data), **May 2026** "Little Red Dot" Abell 2744-QSO1 (JWST NIRSpec IFU gas-velocity sonification), **August 2024** Chandra 25th-anniversary trio (Cassiopeia A, 30 Doradus, NGC 6872), and the **March 2025** *Listen to the Universe* documentary release. All are indexed in prior digests.
>
> Confirmed active resources: [NASA Data Sonifications hub](https://www.nasa.gov/data-sonifications/) · [Chandra Universe of Sound](https://chandra.harvard.edu/sound/listen.html) · [NASA SPDF Sonification](https://spdf.gsfc.nasa.gov/research/sonification/) · [Hearing Hubble interactive](https://science.nasa.gov/mission/hubble/multimedia/online-activities/hearing-hubble/)

---

## GitHub

*New or significantly updated repositories not present in the 2026-06-09 digest.*

| # | Repository | Language | Last Updated | Summary | URL |
|---|-----------|----------|--------------|---------|-----|
| 1 | spectregrams/spectre | Python | 2026-06-10 | SDR-agnostic Python spectrogram recorder supporting RTL-SDR, HackRF, SDRplay, and USRP with explicit solar and Jovian radio astronomy modes; the team is building a global network of low-cost narrowband solar FFT spectrometers. | https://github.com/spectregrams/spectre |
| 2 | saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool | HTML / Python | 2026-04-16 | Browser-based instrument mapping ~2,300 SDSS DR8 galaxy catalogue parameters (redshift, luminosity, morphology) to synthesizer controls via ridge regression, enabling interactive audio-visual galaxy-field exploration and model export as JSON. | https://github.com/saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool |
| 3 | RadioAstronomySoftwareGroup/pyuvdata | Python | 2026-06-08 | Pythonic I/O library supporting all major radio-interferometry data formats (uvfits, CASA measurement sets, uvh5, miriad), actively maintained by the HERA and MWA teams. | https://github.com/RadioAstronomySoftwareGroup/pyuvdata |
| 4 | MWATelescope/mwa_hyperdrive | Rust | 2026-06-09 | GPU-accelerated direction-dependent calibration software for the Murchison Widefield Array radio telescope, written in Rust for high throughput on large interferometric datasets. | https://github.com/MWATelescope/mwa_hyperdrive |
| 5 | Pxomox-Astronomy-Lab/proxmox-astronomy-lab | Jinja / Python | 2026-01-02 | Open-science computational lab for radio astronomy and SDR signal processing built on Proxmox/Kubernetes, publishing the complete research infrastructure stack as reproducible code. | https://github.com/Pxomox-Astronomy-Lab/proxmox-astronomy-lab |
| 6 | sesselastronaut/celestialBodyTracking | JavaScript / Python | — | Tracks real celestial bodies using pyephem and maps their computed sky positions to audio via the WebAudio API, providing a direct celestial-mechanics-to-sound pipeline in the browser. | https://github.com/sesselastronaut/celestialBodyTracking |
| 7 | evanmayer/rtlobs | Python / Jupyter Notebook | — | RTL-SDR radio astronomy observation software supporting total-power integration, hydrogen-line spectral observations, frequency-switched calibration, and optional GPIO/bias-tee hardware control. | https://github.com/evanmayer/rtlobs |
| 8 | james-trayford/strauss | Python | Active | UKRI-funded Python sonification library (JOSS-reviewed v1.0.1) supporting parameter-mapping and audification with built-in presets for astronomical light curves, multi-band images, and spatial/volumetric data. | https://github.com/james-trayford/strauss |

---

## Semantic Scholar

*New entries not present in prior digests.*

| # | Title | Authors | Year | Summary | URL |
|---|-------|---------|------|---------|-----|
| 1 | Kepler Concordia: Designing an Immersive Modular Musical and Scientific Instrument Using Novel Blockchain and Sonification Technologies in XR | Kelly Snook, Tarik Barri et al. | 2018 | Proposes an XR musical instrument that sonifies Kepler's solar-system orbital mechanics, using blockchain/IPFS for data provenance and parameter-mapping sonification to translate planetary data into real-time immersive audio. | https://www.semanticscholar.org/paper/Kepler-Concordia:-Designing-an-Immersive-Modular-in-Snook-Barri/460c3825b1eba8d501081e68411c844a3532096d |
| 2 | Concordia: A musical XR instrument for playing the solar system | Kelly Snook, Tarik Barri | 2020 | Published in *Journal of New Music Research* (Vol 49, No 1), describes Concordia as a mature XR instrument that maps real planetary orbital mechanics to synthesized sound for scientific exploration and artistic performance. | https://www.semanticscholar.org/paper/Concordia:-A-musical-XR-instrument-for-playing-the-Snook-Barri/a83e87a49e5325307f780bc112ac8e111a9f76e4 |

---

## Summary Statistics

| Source | New entries this digest | Notes |
|--------|------------------------|-------|
| arXiv | 7 | 2 sonification experiments (herakoi, blazars); 1 JOSS STRAUSS publication; 2 inclusion/accessibility papers; 1 participant-response study; 1 training platform |
| NASA | 0 | No new releases; prior catalogued releases confirmed active |
| GitHub | 8 | 2 radio/SDR acquisition tools (spectre, rtlobs); 1 galaxy sonification (Baryon); 2 radio telescope pipelines (pyuvdata, mwa_hyperdrive); 1 radio infrastructure (proxmox-astronomy-lab); 1 celestial mechanics audio (celestialBodyTracking); 1 STRAUSS library |
| Semantic Scholar | 2 | Kepler Concordia (2018, 2020) — foundational celestial-mechanics-to-sound papers |
| **Total new** | **17** | |

---

## Open Gaps / Watch List

- **JPL Horizons → audio pipeline**: No dedicated paper or repository yet maps Horizons ephemeris output directly to audio synthesis parameters. `sesselastronaut/celestialBodyTracking` (new this digest) is the closest: it uses pyephem + WebAudio, but does not query the Horizons API. A thin wrapper chaining the Horizons API into STRAUSS or sc3nb would fill this gap completely.
- **OSC + live telescope data**: `interactive-sonification/sc3nb` (prior digest) supplies the OSC↔SuperCollider bridge; no single repo yet chains a live radio telescope or ephemeris stream through OSC in real time.
- **RTL-SDR → audio in one step**: `evanmayer/rtlobs` (new this digest) handles capture; `0xCoto/hydrogen-sonification` (prior digest) handles audio output. Together they close the pipeline; a combined or interoperable release would be the natural next step.
- **Blazar multifrequency follow-up code**: arXiv:2502.01929 (new this digest) demonstrates MIDI-based multi-band sonification of nine blazars; no companion code repository has been identified yet.
- **AuditoryVO ICAD 2026 post-workshop materials**: The June 2026 ICAD conference has likely occurred; post-workshop notebooks and datasets may appear imminently in the AuditoryVO GitHub org.

---

*Digest generated automatically on 2026-06-10. Queries run against arXiv, NASA, GitHub, and Semantic Scholar.*
