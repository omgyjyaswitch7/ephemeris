# EPHEMERIS DIGEST — 2026-06-06

> Auto-collected research on radio astronomy, sonification, and space data.
> Sources: arXiv, NASA, GitHub, Semantic Scholar.
> Query topics: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy.

---

## arXiv

| # | Title | Authors | Date | Summary | Language/Tools | URL |
|---|-------|---------|------|---------|----------------|-----|
| 1 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | Gustavo Magallanes-Guijón, Sergio Mendoza | 2025-02-04 | Sonifies multifrequency variability data from nine blazars using MIDI and Parameter Mapping Sonification (PMSon) to reveal emission patterns audibly. | MIDI, PMSon | https://arxiv.org/abs/2502.01929 |
| 2 | herakoi: a sonification experiment for astronomical data | Michele Ginolfi, Luca Di Mascolo, Anita Zanella | 2024-12-12 | Open-source ML-based tool that maps astronomical images to real-time sound via webcam hand-tracking, targeting education and blind/low-vision accessibility. | Python (inferred, open-source) | https://arxiv.org/abs/2412.09152 |
| 3 | Toward an auditory Virtual Observatory | Adrián García Riber, Francisco Serradilla | 2024-05-18 | Develops sonification prototypes for stellar library and Kepler light curve data using machine learning to broaden access to large astronomical datasets. | Machine learning (unspecified) | https://arxiv.org/abs/2405.11382 |
| 4 | Sound training platform applied to astronomy | Natasha Bertaina Lucero, Johanna Casado, Beatriz García, Gonzalo Cayo | 2024-05-09 | Describes an initial sonification-based training platform for astronomical data analysis aimed at enabling more inclusive, multisensory participation in space science. | — | https://arxiv.org/abs/2405.06042 |
| 5 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Diaz-Merced, Beatriz García | 2024-02-01 | Presents sonoUno, a sonification tool enabling visually impaired scientists to perform astrophysical data analysis through sound-based representations. | sonoUno (Python-based) | https://arxiv.org/abs/2402.00611 |
| 6 | A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response | Kimberly K. Arcand et al. | 2024-03-26 | Converts NASA multi-telescope astronomical data into audio and measures response from both blind/low-vision and sighted participants to evaluate sonification as an accessibility method. | — | https://arxiv.org/abs/2403.18082 |
| 7 | Astronomical images sonification: inclusion or outreach? | Johanna Casado, Beatriz García | 2024-02-01 | Critically examines whether existing astronomical image sonification tools genuinely support research inclusion for people with visual disabilities or primarily serve public outreach. | — | https://arxiv.org/abs/2402.00952 |
| 8 | Sonification of gravitationally lensed gravitational waves | Helena Ubach, Jordi Espuny | 2024-07-12 | Converts gravitational wave data affected by gravitational lensing into sound, leveraging natural wave interference in audio to replicate lensing interference patterns. | — | https://arxiv.org/abs/2407.09588 |
| 9 | The Sonified Hertzsprung-Russell Diagram | Daniela Huppenkothen, Juan Pampin, James R.A. Davenport, James Wenlock | 2023-12-31 | Converts stellar time-series into sound to build an interactive multimedia visualization blending visual and auditory exploration of stellar evolution data. | — | https://arxiv.org/abs/2401.00488 |

---

## NASA

| # | Title | Date | Summary | URL |
|---|-------|------|---------|-----|
| 1 | NASA Open Science Reveals Sounds of Space ("Universe of Sound") | 2024-12-18 (updated 2025-01-22) | NASA converted openly available data from Chandra, Hubble, and Webb into the "Universe of Sound" audio project to make space science accessible to blind/low-vision communities worldwide. | https://science.nasa.gov/open-science/astronomy-data-sonification/ |
| 2 | NASA Data Sonifications (central hub) | Last updated 2025-06-10 | NASA's central repository of 22+ sonified datasets from Hubble, Chandra, and Webb covering nebulae, black holes, and star clusters. | https://www.nasa.gov/data-sonifications/ |
| 3 | Sound of Space Data: Crab Nebula Sonification (NASA JPL) | 2024-06-17 | NuSTAR and Chandra X-ray data of the Crab Nebula mapped to pitched audio, with each X-ray energy band assigned a distinct musical register for accessibility. | https://www.jpl.nasa.gov/videos/sound-of-space-data-crab-nebula-sonification/ |
| 4 | Sonifications — NASA Hubble Mission | — | Collection of interactive Hubble imagery sonifications; includes the "Hearing Hubble" tool where users choose instruments and scanning patterns to sonify their own views. | https://science.nasa.gov/mission/hubble/multimedia/sonifications/ |

> **Note on JPL Horizons + audio mapping:** No dedicated papers found linking JPL Horizons ephemeris data directly to audio/sonification pipelines. The closest match is the NASA JPL Crab Nebula sonification (entry 3 above) and the broader sonoUno/Universe of Sound projects which map telescope data rather than orbital ephemeris. This remains an open niche.

---

## GitHub

| # | Repository | Language | Last Updated | Summary | URL |
|---|-----------|----------|-------------|---------|-----|
| 1 | spacetelescope/astronify | Python / Jupyter Notebook | Active (252+ commits) | STScI's tool for sonifying astronomical time series and light curves, currently in active early development. | https://github.com/spacetelescope/astronify |
| 2 | NASA-IMPACT/data_sonification | Python | Active | Streamlit web application that generates musical audio from numerical NASA data via sonification. | https://github.com/NASA-IMPACT/data_sonification |
| 3 | HSSBoston/constellation-sonifier | Python | 2024-10 | 2024 3M Young Scientist Challenge finalist: translates 6-dimensional constellation data into short musical compositions using music-theoretic algorithms and an AR device. | https://github.com/HSSBoston/constellation-sonifier |
| 4 | evanmayer/rtlobs | Python / Jupyter Notebook | 2025 | Turns RTL-SDR USB dongles into radio astronomy instruments for observing the 21 cm hydrogen line and performing total-power and frequency-switched spectral observations. | https://github.com/evanmayer/rtlobs |
| 5 | spectregrams/spectre | Python | 2026-05-30 | SDR-agnostic application for recording radio signals and generating spectrogram waterfall displays, useful for solar radio monitoring. | https://github.com/spectregrams/spectre |
| 6 | MWATelescope/mwa_hyperdrive | Rust | 2026-06-05 | Calibration software for the Murchison Widefield Array (MWA) radio telescope. | https://github.com/MWATelescope/mwa_hyperdrive |
| 7 | RadioAstronomySoftwareGroup/pyuvdata | Python | 2026-06-05 | Pythonic interface for reading and writing radio astronomy interferometry data in uvfits, Measurement Sets, uvh5, and other formats. | https://github.com/RadioAstronomySoftwareGroup/pyuvdata |
| 8 | lwa-project/bifrost | Python | 2026-02-04 | High-throughput stream processing framework for real-time radio astronomy data pipelines. | https://github.com/lwa-project/bifrost |
| 9 | AstroAccelerateOrg/astro-accelerate | C++ | 2026-04-24 | GPU-accelerated many-core software package for processing time-domain radio astronomy data at scale. | https://github.com/AstroAccelerateOrg/astro-accelerate |
| 10 | ninaspitfire/OpenSpaceKontrol | — | — | Provides telemetry and remote control of Kerbal Space Program vessels via Open Sound Control (OSC) over UDP — notable as an OSC+space-data bridge, albeit in simulation context. | https://github.com/ninaspitfire/OpenSpaceKontrol |

> **Note on OSC + real astronomy:** No active 2024–2026 GitHub projects found coupling OSC (Open Sound Control) directly to live telescope or ephemeris data streams. The AutoFITS2OSC workflow (referenced in arXiv 2405.11382) serializes FITS data to OSC messages but no standalone public repository was located.

---

## Semantic Scholar

| # | Title | Authors | Summary | URL |
|---|-------|---------|---------|-----|
| 1 | RASDR: Benchtop Demonstration of SDR for Radio Astronomy | Bogdan Vacaliuc, Richard Oxley (SARA) | Software Defined Radio device and platform optimised for radio astronomy observations by amateur and professional researchers. | https://www.semanticscholar.org/paper/RASDR:-Benchtop-Demonstration-of-SDR-for-Radio-Vacaliuc-Oxley/be0616d7352b5707dc84e72977e43c39134085ef |
| 2 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Díaz-Merced, Beatriz García | Presents the sonoUno framework and evaluates its theoretical underpinnings for enabling visually impaired participation in astrophysical research. *(Also on arXiv 2402.00611)* | https://www.semanticscholar.org/paper/Analysis-of-astronomical-data-through-sonification:-Casado-D%C3%ADaz-Merced/3365b0a81fee6c448407d4894ae94ad5c484bb91 |
| 3 | Sonification and Sound Design for Astronomy Research, Education and Public Engagement | Multiple authors | Comprehensive survey documenting 98+ global astronomy sonification projects and motivations ranging from scientific discovery to BLV accessibility. *(Also on arXiv 2206.13536)* | https://www.semanticscholar.org/paper/efcab83dc7c81dfe6b720d0ae53ad2f6663c6b55 |

---

## Summary Statistics

| Source | Unique entries |
|--------|---------------|
| arXiv | 9 |
| NASA | 4 |
| GitHub | 10 |
| Semantic Scholar | 3 (2 overlap with arXiv) |
| **Total unique** | **24** |

## Open Gaps / Watch List

- **JPL Horizons → audio pipeline**: No papers or repos found. Opportunity for original work mapping orbital ephemeris data to sound parameters.
- **OSC + live telescope data**: No public implementations found beyond simulation environments.
- **RTL-SDR + direct sonification**: Projects exist for SDR capture and for astronomy sonification, but no repo combining both in a single pipeline was identified.

---

*Digest generated automatically on 2026-06-06. Queries run against arXiv, NASA, GitHub, and Semantic Scholar.*
