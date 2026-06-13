# EPHEMERIS DIGEST — 2026-06-13

> Automated research collection on radio astronomy, sonification, and space data.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> Search terms: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy

---

## arXiv

| # | Title | Authors | Date | URL | Summary | Language / Tools |
|---|-------|---------|------|-----|---------|-----------------|
| 1 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | Gustavo Magallanes-Guijón, Sergio Mendoza | 2025-02-04 | https://arxiv.org/abs/2502.01929 | Converts multifrequency light curves of nine blazars (optical, X-ray, γ-ray) into sound via MIDI-based Parameter Mapping Sonification to reveal temporal variability patterns across energy regimes. | MIDI, PMSon |
| 2 | STRAUSS: Sonification Tools & Resources for Analysis Using Sound Synthesis | James W. Trayford, Samantha Youles, Chris Harrison, Rose Shepherd, Nicolas Bonne | 2025-04-02 | https://arxiv.org/abs/2504.01660 | A free, flexible Python package providing multi-context sonification utilities spanning scientific education, communication, and technical data analysis, underpinning the Audio Universe Collaboration. | Python |
| 3 | herakoi: a sonification experiment for astronomical data | Michele Ginolfi, Luca Di Mascolo, Anita Zanella | 2024-12-12 | https://arxiv.org/abs/2412.09152 | Open-source software that maps hand-gesture positions tracked by a webcam to image coordinates, translating visual properties of astronomical images into real-time sound for accessibility and education. | — |
| 4 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Diaz-Merced, Beatriz García | 2024-02-01 | https://arxiv.org/abs/2402.00611 | Presents sonoUno, a web-based platform that converts astronomical datasets into sound and evaluates the interface against ISO accessibility standards to support visually-impaired scientists. | — |
| 5 | What does the Universe sound like? | Francesco Iacovelli | 2026-04-01 | https://arxiv.org/abs/2603.29996 | Sonifies gravitational-wave signals from a wide range of cosmic sources into audio tracks released under Creative Commons, with companion code and WAV files on GitHub. | — (code: https://github.com/FrancescoIacovelli/universal_harmony) |
| 6 | Unseen Astronomy | James W. Trayford | 2026-04-10 | https://arxiv.org/abs/2604.09250 | Reviews multimodal approaches—sonification, tactile displays, and alternative sensory channels—for expanding astronomy research and communication beyond visual-only data representations. | Python (STRAUSS, Astronify, JDAViz) |
| 7 | Isolating Broadband Radio Technosignatures (BRaTs): A Framework for Detecting Planetary-Scale Leakage | Michael A. Garrett | 2026-05-11 | https://arxiv.org/abs/2605.10212 | Proposes a multi-parameter diagnostic framework using deep radio surveys and VLBI interferometry to distinguish unintentional broadband electromagnetic leakage from advanced civilizations from natural astrophysical sources. | — |
| 8 | Observations of the 21 cm HI Line from the Milky Way galaxy using Pyramidal Horn Radio Telescope | Kaustav Bhattacharjee, Himanshu Grover, P. Arumugam | 2025-12-22 | https://arxiv.org/abs/2512.19262 | Describes an affordable pyramidal horn telescope with an SDR-based drift-scan pipeline that detects neutral hydrogen emission and maps Milky Way spiral arm structure. | SDR pipeline; GNU Radio |
| 9 | ASTROFLOW: A Real-Time End-to-End Pipeline for Radio Single-Pulse Searches | Guanhong Lin et al. | 2025-11-04 | https://arxiv.org/abs/2511.02328 | A GPU-accelerated, YOLO-powered real-time pipeline for detecting fast radio bursts that processes incoming radio astronomy data faster than live data rates on consumer GPUs. | C++/CUDA, Python, OpenMP |

---

## NASA

| # | Title | Date | URL | Summary | Language / Tools |
|---|-------|------|-----|---------|-----------------|
| 1 | "Cosmic Echoes" Audio Activation | 2026-05-08 | https://svs.gsfc.nasa.gov/14983 | An ~8-minute curated audio experience produced by NASA SVS that combines historic spacecraft recordings, real electromagnetic wave recordings, and scientific sonification of astronomical data into a cohesive spatial soundscape. | — |
| 2 | NASA Data Sonifications Hub | (ongoing) | https://www.nasa.gov/data-sonifications/ | Central NASA portal aggregating multi-telescope sonifications from Chandra X-ray Observatory, Hubble Space Telescope, and James Webb Space Telescope, mapping brightness and position data to pitch and volume. | — |
| 3 | JPL Sound of Space Data: Crab Nebula Sonification | (ongoing) | https://www.jpl.nasa.gov/videos/sound-of-space-data-crab-nebula-sonification/ | JPL video demonstrating how multi-wavelength Crab Nebula data (X-ray, optical, infrared) are mapped to distinct musical pitches and instrument timbres to create a layered audio portrait of a supernova remnant. | — |

---

## GitHub

| # | Repository | Last Updated | URL | Summary | Language |
|---|-----------|-------------|-----|---------|---------|
| 1 | Baryon: Audio-Visual Galaxy Inspection Sonification Tool | 2026-04 | https://github.com/saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool | Self-contained browser app for navigating ~2,300 SDSS DR8 galaxies with real-time PeriodicWave audio synthesis mapped to catalog parameters (morphology, flux, redshift) via Ridge regression. | HTML, Python |
| 2 | rtl-ml: AI-Powered RTL-SDR Signal Classifier | 2026 | https://github.com/TrevTron/rtl-ml | Random Forest classifier running on ARM SBCs (Raspberry Pi 5) that achieves 96.9% accuracy identifying seven real-world radio signal types from RTL-SDR Blog V4 hardware. | Python |
| 3 | r-xue/pipeline | 2026-06-12 | https://github.com/r-xue/pipeline | Actively maintained CASA-based radio astronomy data processing pipeline with recent commits through June 2026. | Python |
| 4 | ratt-ru/xarray-ms | 2026-06-12 | https://github.com/ratt-ru/xarray-ms | Provides xarray MSv4 views over CASA MeasurementSet v2 files, enabling modern array-computing workflows for radio astronomy data. | Python |
| 5 | avikhagol/avica (AVICA VLBI Pipeline) | 2026-06-12 | https://github.com/avikhagol/avica | Automated batch-processing pipeline for blind calibration of multi-frequency VLBI data using rPICARD within CASA. | Python |
| 6 | Majimety/ATMOS | 2026-06-12 | https://github.com/Majimety/ATMOS-Atacama-Telescope-Monitoring-and-Operations-System | SCADA system for monitoring and controlling radio telescope arrays at the Atacama Desert Observatory with real-time dashboards. | Python |
| 7 | kyleaoman/martini | 2026-06-11 | https://github.com/kyleaoman/martini | Creates mock spatially-resolved spectral-line radio observations of simulated galaxies for direct comparison with telescope data. | Python |
| 8 | AlanLoh/nenupy | 2026-06-11 | https://github.com/AlanLoh/nenupy | Python package for NenuFAR low-frequency radio telescope data analysis and pipeline processing. | Python / Jupyter |
| 9 | askap-vast/vast-pipeline | 2026-06-11 | https://github.com/askap-vast/vast-pipeline | Radio transient detection pipeline for the VAST (Variables and Slow Transients) ASKAP survey project. | Python |
| 10 | rtlobs | (active) | https://github.com/evanmayer/rtlobs | Python/Jupyter toolkit for 21 cm hydrogen-line observation, total-power radiometry, and spectral calibration using consumer RTL-SDR dongles. | Python, Jupyter Notebook |
| 11 | KnoxAstro/sonification-project | (active) | https://github.com/KnoxAstro/sonification-project | Knox College web project converting data from Jupiter's moons, M13, Saturn, and the TRAPPIST system into interactive browser-based audio visualizations. | JavaScript |

---

## Semantic Scholar

| # | Title | Authors | URL | Summary | Language / Tools |
|---|-------|---------|-----|---------|-----------------|
| 1 | XSONIFY SONIFICATION TOOL FOR SPACE PHYSICS | Candey, Schertenleib | https://www.semanticscholar.org/paper/XSONIFY-SONIFICATION-TOOL-FOR-SPACE-PHYSICS-Candey-Schertenleib/80ee2e773d67ad6a24f51e3ecabfa76ed5d2a7b1 | xSonify extends NASA Space Physics Data Facility capabilities to visually-impaired students and researchers by converting space physics datasets into sound via the JavaSound API. | Java |
| 2 | Sonification of ACE Level 2 Solar Wind Data | Alexander, Zurbuchen | https://www.semanticscholar.org/paper/Sonification-of-Ace-Level-2-Solar-Wind-Data-Alexander-Zurbuchen/1c7a8b1f1c271a7d7fbdfe06b69be339bb46925e | Demonstrates that solar wind ionic composition sonification successfully identified data anomalies including Voyager 2 instrument issues and promising carbon-ion ratios for measuring solar wind type. | — |
| 3 | Concordia: A musical XR instrument for playing the solar system | Snook, Barri | https://www.semanticscholar.org/paper/Concordia:-A-musical-XR-instrument-for-playing-the-Snook-Barri/a83e87a49e5325307f780bc112ac8e111a9f76e4 | A sonified extended-reality model of the eight planets evaluated with end users to test whether listeners could discern planetary characteristics such as orbital period and mass through audio alone. | — |
| 4 | Web Sonification Sandbox | Kondak, Liang | https://www.semanticscholar.org/paper/Web-Sonification-Sandbox-an-Easy-to-Use-Web-for-and-Kondak-Liang/6b27831d1e670ba7eaaacec619a984e06a008857 | A browser-based platform enabling non-programmers to sonify arbitrary datasets and equations to facilitate more inclusive and multisensory participation in space science. | — |

---

## Notes

- **JPL Horizons / Celestial Mechanics Audio**: No dedicated sonification papers explicitly using JPL Horizons ephemeris data were found in this sweep; the closest results are the Concordia XR solar-system instrument (Semantic Scholar) and the MIDI blazar mapping paper (arXiv:2502.01929). Future searches should target "ephemeris MIDI" or "orbital elements audio."
- **OSC (Open Sound Control)**: No new 2025–2026 arXiv papers explicitly combining OSC with astronomy were found; historical use appears in the Chison/SuperCollider pipeline (GitHub) and CosMonic. The STRAUSS package (arXiv:2504.01660) is the current state-of-the-art Python sonification framework.
- **Deduplication**: "Analysis of astronomical data through sonification" (Casado et al.) appears on both arXiv and Semantic Scholar; it is listed under arXiv only.
- All URLs verified at time of collection (2026-06-13).

---

*Generated by Claude Code · Ephemeris Project · 2026-06-13*
