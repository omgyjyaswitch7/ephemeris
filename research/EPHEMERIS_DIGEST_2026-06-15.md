# EPHEMERIS DIGEST — 2026-06-15

> Automated research digest covering sonification, radio astronomy, and space data projects.
> Sources: arXiv · NASA · GitHub · Semantic Scholar

---

## arXiv

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | 2025-02-04 (v3: 2026-03-04) | https://arxiv.org/abs/2502.01929 | Applies MIDI Parameter Mapping Sonification to the multifrequency light curves of nine blazars using open astronomical databases to reveal variability patterns across optical, X-ray, and gamma-ray regimes. | — (MIDI/PMSon methodology) |
| 2 | herakoi: a sonification experiment for astronomical data | 2024-12-12 | https://arxiv.org/abs/2412.09152 | Presents an open-source ML tool that translates astronomical images into real-time sound via webcam hand-gesture tracking, enabling auditory exploration of image properties for accessibility and outreach. | — |
| 3 | A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response | 2024-03-26 | https://arxiv.org/abs/2403.18082 | Evaluates how both sighted and blind/low-vision participants respond (in terms of learning, enjoyment, and confidence) to NASA multi-telescope astronomical data converted into audio representations. | — |
| 4 | Astronomical images sonification: inclusion or outreach? | 2024-02-01 | https://arxiv.org/abs/2402.00952 | Examines whether current sonification tools in astronomy primarily serve outreach or can enable people with functional diversity to participate as active researchers using the sonoUno platform. | — |
| 5 | The Sonified Hertzsprung-Russell Diagram | 2023-12-31 | https://arxiv.org/abs/2401.00488 | Converts stellar time-series data from the Hertzsprung-Russell Diagram into sound, producing an interactive multimedia visualization that allows both visual and auditory exploration of stellar properties. | — |
| 6 | Sonification of gravitationally lensed gravitational waves | 2024-07-12 | https://arxiv.org/abs/2407.09588 | Converts LIGO gravitational wave data into audio to demonstrate how gravitational lensing creates multiple wave images and audible interference patterns via sound's natural wave physics. | — |
| 7 | Explainable machine learning workflows for radio astronomical data processing | 2026-03-17 | https://arxiv.org/abs/2603.16350 | Proposes a hybrid fuzzy rule-based inference + deep learning framework to make ML-aided radio astronomy calibration pipelines more explainable to astronomers without sacrificing accuracy. | — |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | Listen to the Universe: New NASA Sonifications and Documentary | 2024-02-28 | https://www.nasa.gov/missions/chandra/listen-to-the-universe-new-nasa-sonifications-and-documentary/ | Released three new multi-telescope sonifications — MSH 11-52 (supernova remnant), M74 (spiral galaxy combining Webb + Hubble + Chandra data), and the Jellyfish Nebula (IC 443) — alongside a documentary on NASA+. |
| 2 | NASA Data Sonifications Hub | ongoing | https://www.nasa.gov/data-sonifications/ | Aggregation hub for all NASA sonification projects translating Chandra, Hubble, Webb, and Spitzer data into audio, with brightness and position mapped to pitch and volume. |
| 3 | NASA Open Science — Astronomy Data Sonification | ongoing | https://science.nasa.gov/open-science/astronomy-data-sonification/ | Overview of the "A Universe of Sound" initiative converting multi-telescope astronomical data into audio via collaboration with SYSTEM Sounds (Matt Russo & Andrew Santaguida), hosted at chandra.harvard.edu/sound/. |
| 4 | Hubble Sonifications Collection | ongoing | https://science.nasa.gov/mission/hubble/multimedia/sonifications/ | Collection of over ten Hubble image sonifications (Mice Galaxies, V838 Mon, Black Hole in M87, Bubble Nebula, etc.) using radar-scan and brightness-to-pitch mappings for multimodal astronomical exploration. |
| 5 | NASA Space Physics Data Facility — xSonify | ongoing | https://spdf.gsfc.nasa.gov/research/sonification/ | xSonify extends NASA SPDF space physics data for visually-impaired students and researchers by providing a sonification analysis tool built on the JavaSound API with local and web-service data access. |

---

## GitHub

| # | Repository | Updated | URL | Summary | Language |
|---|-----------|---------|-----|---------|----------|
| 1 | AuditoryVO/ICAD2026_Workshop | 2026-06-13 | https://github.com/AuditoryVO/ICAD2026_Workshop | Workshop repo for ICAD 2026 presenting SoniAladin, a Spanish Virtual Observatory application that transforms Aladin Sky Atlas astronomical data into audible representations for accessible sky exploration. | Python |
| 2 | AuditoryVO/Hands_on_astronomical_data_sonification | 2026-06-14 | https://github.com/AuditoryVO/Hands_on_astronomical_data_sonification | Hands-on educational workshop materials from ESMUC June 2026 teaching participants to convert astronomical datasets into auditory representations for scientific analysis and interpretation. | Jupyter Notebook |
| 3 | NJRSAM003/FaradayExplorer | 2026-06-15 | https://github.com/NJRSAM003/FaradayExplorer | Interactive Faraday-depth polarisation model viewer for radio astronomy enabling visualization and exploration of Faraday rotation in polarised radio sources. | Python |
| 4 | Y-Masayuki/AJISAI | 2026-06-14 | https://github.com/Y-Masayuki/AJISAI | Automated Justification-based Imaging and Self-calibration for ALMA Infrastructure — a radio astronomy imaging pipeline targeting ALMA telescope arrays. | Python |
| 5 | Majimety/ATMOS | 2026-06-13 | https://github.com/Majimety/ATMOS-Atacama-Telescope-Monitoring-and-Operations-System | SCADA system for real-time monitoring and control of radio telescope arrays at the Atacama Desert Observatory, providing automated operations support. | Python |
| 6 | sgoudelis/ground-station | 2026-06-12 | https://github.com/sgoudelis/ground-station | All-in-one satellite monitoring suite with SDR hardware support (RTL-SDR, SoapySDR, UHD/USRP), real-time orbit tracking, IQ recording/playback, and automated observation scheduling via a web interface. | JavaScript, Python |
| 7 | spacetelescope/astronify | active | https://github.com/spacetelescope/astronify | STScI's open-source Python package for converting astronomical time-series data (especially light curves) into sound, enabling auditory exploration of MAST-hosted observations. | Python, Jupyter Notebook |
| 8 | TrevTron/rtl-ml | 2026 | https://github.com/TrevTron/rtl-ml | AI-powered radio signal classifier using RTL-SDR + ARM SBC that identifies FM, NOAA Weather, APRS, FRS/GMRS, ISM sensor, and pager signals with 96.9% accuracy on a $220 hardware setup. | Python |
| 9 | evanmayer/rtlobs | active | https://github.com/evanmayer/rtlobs | RTL-SDR-based radio astronomy observation software for total power integration, 21 cm hydrogen line observations, and frequency-switched spectral observations, tested on Raspberry Pi 4. | Python |
| 10 | ideoforms/isobar | active | https://github.com/ideoforms/isobar | Python library for creating and manipulating musical patterns for algorithmic composition, generative music, and data sonification — supports MIDI file/event output and OSC message sending. | Python |
| 11 | lintian233/astroflow | 2026-06-04 | https://github.com/lintian233/astroflow | Real-time GPU-accelerated single-pulse/FRB (Fast Radio Burst) search pipeline for radio astronomy data processing. | Python |

---

## Semantic Scholar

| # | Title | URL | Summary | Language/Tool |
|---|-------|-----|---------|---------------|
| 1 | XSONIFY SONIFICATION TOOL FOR SPACE PHYSICS | https://www.semanticscholar.org/paper/XSONIFY-SONIFICATION-TOOL-FOR-SPACE-PHYSICS-Candey-Schertenleib/80ee2e773d67ad6a24f51e3ecabfa76ed5d2a7b1 | Extends NASA Space Physics Data Facility capabilities for visually-impaired users by implementing a sonification data analysis tool that accesses space physics data locally or via web services. | Java (JavaSound API) |
| 2 | Analysis of astronomical data through sonification: reaching more inclusion for visually disabled scientists | https://www.semanticscholar.org/paper/Analysis-of-astronomical-data-through-sonification:-Casado-D%C3%ADaz-Merced/3365b0a81fee6c448407d4894ae94ad5c484bb91 | Demonstrates that the sonoUno software enables visually disabled scientists to analyze astronomical data through sound, advancing research inclusion beyond purely outreach applications. | sonoUno (Python-based) |
| 3 | Toward a data sonification design space map | https://www.semanticscholar.org/paper/Toward-a-data-sonification-design-space-map-Campo/734b78c06fe151715a23b2f8ea8796b18f3b8d28 | Introduces a systematic meta-framework for reasoning about and designing experimental sonifications by mapping physical data quantities to auditory parameters across diverse dataset types. | — |

---

## Notes

- **OSC / Open Sound Control + Astronomy**: No new dedicated arXiv or Semantic Scholar papers specifically combining OSC protocol with astronomy were found in the 2025–2026 window. The `ideoforms/isobar` library (GitHub) supports OSC output and is used in sonification workflows. Prior art exists (see SonART framework on Semantic Scholar).
- **JPL Horizons + Audio**: No dedicated papers mapping JPL Horizons ephemeris data to audio/sonification were found. The Horizons API is referenced in visualization projects (e.g., Interstellar Signature, 2025), but not yet paired with audio mapping in the indexed literature.
- **Celestial Mechanics Audio**: Closest matches are the Sonified H-R Diagram (arXiv:2401.00488) and the blazars sonification (arXiv:2502.01929); no dedicated celestial mechanics + audio papers surfaced in this run.
- **Deduplication**: All entries are unique by URL and title. Papers appearing across multiple sources (e.g., arXiv:2403.18082 cited in both search results and Semantic Scholar) are recorded once under their primary source.

---

*Generated by automated research routine · 2026-06-15*
