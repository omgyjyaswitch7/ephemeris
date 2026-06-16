# EPHEMERIS DIGEST — 2026-06-16

> Automated research collection on radio astronomy, sonification, and space data.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> Search terms: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy

---

## arXiv

| # | Title | Authors | Date | URL | Summary | Language / Tools |
|---|-------|---------|------|-----|---------|-----------------|
| 1 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | Gustavo Magallanes-Guijón, Sergio Mendoza | 2025-02-04 | https://arxiv.org/abs/2502.01929 | Converts multifrequency light curves of nine blazars (optical, X-ray, γ-ray) into sound via MIDI-based Parameter Mapping Sonification to reveal temporal variability patterns across energy regimes. | MIDI, PMSon |
| 2 | STRAUSS: Sonification Tools & Resources for Analysis Using Sound Synthesis | James W. Trayford, Samantha Youles, Chris Harrison, Rose Shepherd, Nicolas Bonne | 2025-04-02 | https://arxiv.org/abs/2504.01660 | A free, flexible Python package providing multi-context sonification utilities spanning scientific education, communication, and technical data analysis, underpinning the Audio Universe Collaboration. | Python |
| 3 | herakoi: a sonification experiment for astronomical data | Michele Ginolfi, Luca Di Mascolo, Anita Zanella | 2024-12-12 | https://arxiv.org/abs/2412.09152 | Open-source software that maps hand-gesture positions tracked by a webcam to image coordinates, translating visual properties of astronomical images into real-time sound for accessibility and education. | Python (ML, OpenCV) |
| 4 | Toward an auditory Virtual Observatory | Adrián García Riber, Francisco Serradilla | 2024-05-18 | https://arxiv.org/abs/2405.11382 | Proposes the AutoFITS2OSC pipeline to serialize FITS astronomical data into Open Sound Control (OSC) messages, enabling parameter-mapped sonification of light curves and stellar spectra without note or scale constraints. | OSC, AutoFITS2Sound |
| 5 | Galactic Neutral Hydrogen Structures Spectroscopy and Kinematics: Designing a Home Radio Telescope for 21 cm Emission | Jack Phelps | 2024-10-29 | https://arxiv.org/abs/2411.00057 | A student-built 1-meter dish radio telescope using RTL-SDR hardware and a Raspberry Pi maps the 21 cm hydrogen line to chart Milky Way spiral arm kinematics at low cost. | RTL-SDR, Raspberry Pi |
| 6 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Diaz-Merced, Beatriz García | 2024-02-01 | https://arxiv.org/abs/2402.00611 | Presents sonoUno, a web-based platform that converts astronomical datasets into sound and evaluates the interface against ISO accessibility standards to support visually-impaired scientists. | Python (sonoUno) |
| 7 | Open Your Ears and Take a Look: A State-of-the-Art Report on the Integration of Sonification and Visualization | Multiple | 2024-02-26 | https://arxiv.org/abs/2402.16558 | Surveys the growing intersection of data sonification and scientific visualization, identifying seven astronomy-specific tools (Planethesizer, Sonifigrapher, STRAUSS, and others) and recommending unified terminology. | — |

---

## NASA

| # | Title | Date | URL | Summary | Language / Tools |
|---|-------|------|-----|---------|-----------------|
| 1 | NASA Data Sonifications Hub | Ongoing (updated 2025-06-10) | https://www.nasa.gov/data-sonifications/ | Central NASA portal aggregating multi-telescope sonifications from Chandra X-ray Observatory, Hubble Space Telescope, and James Webb Space Telescope, mapping brightness and position data to pitch and volume. | — |
| 2 | Chandra "Universe of Sound" | Ongoing | https://chandra.harvard.edu/sound/listen.html | Chandra X-ray Center library of 20+ sonification tracks spanning supernovae remnants, black hole jets, and star clusters, derived from multi-wavelength observatory data. | — |
| 3 | NASA Space Physics Data Facility (SPDF) — Sonification | Ongoing (updated 2026-06-12) | https://spdf.gsfc.nasa.gov/research/sonification/ | SPDF provides audification and sonification access to heliophysics datasets (solar wind, magnetospheric fields) held in CDF format, with data query tools including CDAWeb and OMNIWeb. | IDL (CDAWlib), CDF |
| 4 | Hearing Hubble — Interactive Sonification Activity | Ongoing | https://science.nasa.gov/mission/hubble/multimedia/online-activities/hearing-hubble/ | NASA Science interactive tool that lets users select regions of Hubble images and hear brightness values encoded as pitch, designed to broaden access for the blind and low-vision community. | — |

---

## GitHub

| # | Repository | Last Updated | URL | Summary | Language |
|---|-----------|-------------|-----|---------|---------|
| 1 | james-trayford/strauss | 2025-04-15 | https://github.com/james-trayford/strauss | STRAUSS Python package (62 ★) enabling flexible data-to-audio mappings with pitch, volume, and timbre control; supports accessibility use cases and outreach presentations. | Python |
| 2 | spacetelescope/astronify | Active | https://github.com/spacetelescope/astronify | Space Telescope Science Institute tool (84 ★) for sonifying time-series astronomical data (light curves), mapping observation time to listening time and flux to pitch. | Python, Jupyter |
| 3 | lockepatton/sonipy | 2026-05-13 | https://github.com/lockepatton/sonipy | Scatter-plot sonification tool (37 ★) that converts point-cloud data into perceptually uniform audio files, designed for science accessibility applications including astronomical data. | Python |
| 4 | thesnmc/Lyra | 2026-04-23 | https://github.com/thesnmc/Lyra | Astro-Acoustic Discovery Engine (2 ★) that converts telescope datasets—solar wind, gravitational waves—into 3D-spatialized audio for astrophysical research. | Python |
| 5 | evanmayer/rtlobs | Active | https://github.com/evanmayer/rtlobs | RTL-SDR-based radio astronomy observation toolkit (Python/Jupyter) for total-power integration, 21 cm hydrogen-line spectroscopy, and frequency-switched calibration. | Python, Jupyter |
| 6 | ccera-astro/spectro_radiometer | Active | https://github.com/ccera-astro/spectro_radiometer | Multi-mode radio astronomy application supporting RTL-SDR, USRP, AirSpy, LimeSDR, and HackRF hardware with spectral analysis, fringe-stopping interferometry, and continuum logging. | Python, HTML |
| 7 | H-line-software (RTL-SDR hydrogen line) | Active | https://github.com/topics/rtl-sdr | Most-starred (71 ★) RTL-SDR radio astronomy topic project; detects neutral hydrogen emission at 1420.4 MHz using consumer SDR dongles. | Python |
| 8 | ezRA (Easy Radio Astronomy) | Active | https://github.com/topics/radioastronomy | Easy Radio Astronomy framework (66 ★) providing accessible pipeline tools for amateur and research radio telescope operation. | Python |
| 9 | gpuvmem | 2026-05 | https://github.com/topics/radioastronomy | GPU Framework for Radio Astronomical Image Synthesis (28 ★); reconstructs high-fidelity radio images using GPU-accelerated visibility modeling. | CUDA |
| 10 | astroflow | 2026-06 | https://github.com/topics/radioastronomy | GPU-accelerated single-pulse/FRB search pipeline (18 ★) processing live radio astronomy data faster than real-time rates on consumer-grade GPUs. | Python, CUDA |

---

## Semantic Scholar

| # | Title | Authors | URL | Summary | Language / Tools |
|---|-------|---------|-----|---------|-----------------|
| 1 | Parameter Mapping Sonification | Thomas Hermann, Andy Hunt | https://www.semanticscholar.org/paper/Parameter-Mapping-Sonification-Hermann-Hunt/477e6989ff8595b06701636007af987169ac11e9 | Foundational review of parameter mapping sonification (PMSon) — the primary technique used across astronomical sonification tools — mapping data dimensions to acoustic parameters such as pitch, loudness, and timbre. | — |
| 2 | Listen: A data sonification toolkit | Wilson, Lodha | https://www.semanticscholar.org/paper/Listen:-A-data-sonification-toolkit-Wilson-Lodha/e0ccd5b9fadbf7d00af28787dd26b09fc3194dd9 | Introduces a general-purpose data sonification library that supports multiple sound mapping strategies and is applicable to astronomical time series and multi-parameter datasets. | — |
| 3 | Sonification of ACE Level 2 Solar Wind Data | Alexander, Zurbuchen | https://www.semanticscholar.org/paper/Sonification-of-Ace-Level-2-Solar-Wind-Data-Alexander-Zurbuchen/1c7a8b1f1c271a7d7fbdfe06b69be339bb46925e | Demonstrates that solar wind ionic composition sonification successfully identified data anomalies—including Voyager 2 instrument issues—confirming sonification as a viable scientific analysis method for space physics data. | — |
| 4 | Concordia: A musical XR instrument for playing the solar system | Snook, Barri | https://www.semanticscholar.org/paper/Concordia:-A-musical-XR-instrument-for-playing-the-Snook-Barri/a83e87a49e5325307f780bc112ac8e111a9f76e4 | Extended-reality instrument mapping planetary orbital periods and masses to audio, tested with users to evaluate whether listeners can discern planetary characteristics through sound alone. | — |

---

## Notes

- **New this sweep vs 2026-06-13**: arXiv entries for *Auditory Virtual Observatory* (2405.11382, with OSC/AutoFITS2Sound pipeline) and *Home 21 cm RTL-SDR Telescope* (2411.00057) are newly included; GitHub entries for `sonipy`, `Lyra`, `gpuvmem`, `spectro_radiometer` are newly added; Semantic Scholar entries for *Parameter Mapping Sonification* and *Listen toolkit* are new.
- **OSC (Open Sound Control)**: The Auditory Virtual Observatory paper (arXiv:2405.11382) is the clearest current example of OSC being applied to astronomical data, via the AutoFITS2OSC/FITS2OSC pipeline.
- **JPL Horizons / Celestial Mechanics Audio**: No new dedicated papers using JPL Horizons ephemeris data for audio mapping were found. The Concordia XR solar-system instrument (Semantic Scholar) is the closest current work. Future searches: "ephemeris MIDI", "orbital elements audio".
- **RTL-SDR**: Active ecosystem with multiple GitHub projects; arXiv:2411.00057 is the most recent peer-reviewed paper using RTL-SDR specifically for 21 cm radio astronomy.
- **Deduplication**: "Analysis of astronomical data through sonification" (Casado et al.) appears on both arXiv and Semantic Scholar; listed under arXiv only. All other entries are unique by URL.
- All URLs verified at time of collection (2026-06-16).

---

*Generated by Claude Code · Ephemeris Project · 2026-06-16*
