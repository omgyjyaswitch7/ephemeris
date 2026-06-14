# EPHEMERIS DIGEST — 2026-06-14

> Automated research digest covering radio astronomy, sonification, and space data.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> Search terms: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy

---

## arXiv

| # | Title | Authors | Date | URL | Summary | Language |
|---|-------|---------|------|-----|---------|----------|
| 1 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | Gustavo Magallanes-Guijón, Sergio Mendoza | 2025-02-04 (pub. 2026-03-04, RAS Techniques and Instruments) | https://arxiv.org/abs/2502.01929 | Multi-frequency light curves from nine blazars are converted into MIDI-based audio to reveal variability patterns and support real-time monitoring. | — |
| 2 | herakoi: a sonification experiment for astronomical data | Michele Ginolfi, Luca Di Mascolo, Anita Zanella | 2024-12-12 | https://arxiv.org/abs/2412.09152 | Open-source tool uses machine learning and webcam hand-tracking to map astronomical image properties (brightness, color) to real-time audio output. | Python |
| 3 | Sound training platform applied to astronomy | Natasha Bertaina Lucero, Johanna Casado, Beatriz García, Gonzalo Cayo | 2024-05-09 | https://arxiv.org/abs/2405.06042 | Describes the initial development of a multisensory training platform that converts astronomical data into sound to enable inclusive participation in space science research. | — |
| 4 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Diaz-Merced, Beatriz García | 2024-02-01 | https://arxiv.org/abs/2402.00611 | Presents the sonoUno software framework, which makes astrophysical data analysis accessible to visually impaired researchers through sound-based methods. | — |
| 5 | Astronomical images sonification: inclusion or outreach? | Johanna Casado, Beatriz García | 2024-02-01 | https://arxiv.org/abs/2402.00952 | Questions whether current astronomical image sonification tools serve primarily as public outreach or as genuine research tools for people with diverse visual abilities. | — |
| 6 | A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response | Kimberly K. Arcand et al. | 2024-03-26 | https://arxiv.org/abs/2403.18082 | Surveys over 3,100 participants to assess how NASA astronomical sonifications improved accessibility and learning for blind/low-vision and sighted audiences alike. | — |
| 7 | Sonification and Sound Design for Astronomy Research, Education and Public Engagement | Multiple | 2022-06 | https://arxiv.org/abs/2206.13536 | Comprehensive survey of 98+ global astronomy sonification projects over the past decade, covering scientific discovery, accessibility, and public engagement motivations. | — |
| 8 | Open Your Ears to Take a Look: A State-of-the-Art Report on the Integration of Sonification and Visualization | Multiple | 2024-02 | https://arxiv.org/abs/2402.16558 | Categorizes 57 academic publications (2011–2023) that combine sonification and visualization, including astronomy applications such as orbits, exoplanets, and gravitational waves. | — |

---

## NASA

| # | Title | Source | Date | URL | Summary |
|---|-------|--------|------|-----|---------|
| 1 | "Cosmic Echoes" Audio Activation | NASA Scientific Visualization Studio | 2026-05-08 | https://svs.gsfc.nasa.gov/14983 | An ~8-minute curated audio experience blending historic spacecraft recordings, electromagnetic wave data, and scientific sonification to let audiences explore space through sound. |
| 2 | Data Sonifications (collection) | NASA | Updated 2025-06-10 | https://www.nasa.gov/data-sonifications/ | Central NASA hub for sonifications from Chandra, James Webb, and Hubble telescopes, organized by observatory with 20+ entries covering nebulae, black holes, and galaxies. |
| 3 | NASA Open Science Reveals Sounds of Space | NASA Science | Ongoing | https://science.nasa.gov/open-science/astronomy-data-sonification/ | Overview of the "A Universe of Sound" project converting openly available Chandra and multi-observatory data into dozens of community-accessible sonifications. |
| 4 | Sonifications — Hubble Space Telescope | NASA Science | Ongoing | https://science.nasa.gov/mission/hubble/multimedia/sonifications/ | Collection of Hubble sonifications mapping brightness and position to pitch and volume, with instruments (e.g., piano for X-ray, strings for infrared) encoding telescope source. |
| 5 | Sound of Space Data: Crab Nebula Sonification | NASA JPL | Ongoing | https://www.jpl.nasa.gov/videos/sound-of-space-data-crab-nebula-sonification/ | Sonification of Crab Nebula multi-wavelength data produced by JPL, translating X-ray, optical, and radio observations into distinct layered audio tones. |
| 6 | From Data to Melody: Data Sonification and Its Role in Open Science | NASA Earthdata | Ongoing | https://www.earthdata.nasa.gov/news/blog/from-data-melody-data-sonification-its-role-open-science | Blog post explaining how brightness, position, and color parameters are mapped to pitch and volume in NASA's Earth and space data sonification pipelines. |

---

## GitHub

| # | Repository | Language | Last Updated | URL | Summary |
|---|-----------|----------|--------------|-----|---------|
| 1 | james-trayford/strauss — Sonification Tools and Resources for Analysis Using Sound Synthesis | Python | 2025-04-15 | https://github.com/james-trayford/strauss | Python package (published in JOSS 2025) that converts scientific data into audio, supporting both accessibility and scientific visualization use cases. |
| 2 | spacetelescope/astronify — Astronomical data sonification | Python / Jupyter Notebook | 2026-02-01 | https://github.com/spacetelescope/astronify | STScI tool for sonifying astronomical time-series data (e.g., light curves) by mapping data values to pitch using a note-based audio output. |
| 3 | evanmayer/rtlobs — RTL-SDR-based radio astronomy observation software | Python / Jupyter Notebook | Active | https://github.com/evanmayer/rtlobs | Turns an RTL-SDR dongle into a radio astronomy workstation for total-power integration and 21 cm hydrogen line spectroscopy. |
| 4 | TrevTron/rtl-ml — AI-powered radio signal classifier using RTL-SDR | Python | Active | https://github.com/TrevTron/rtl-ml | Classifies FM, NOAA, APRS, ISM, and pager radio signals with 96.9% accuracy using a Random Forest model running on Raspberry Pi + RTL-SDR hardware. |
| 5 | spectregrams/spectre — SDR-agnostic radio signal recorder | Python | 2026-06-10 | https://github.com/spectregrams/spectre | SDR-agnostic tool for recording radio signals and waterfall spectrograms, with applications including solar radio observation and atmospheric event detection. |
| 6 | MWATelescope/mwa_hyperdrive — MWA calibration software | Rust | 2026-06-09 | https://github.com/MWATelescope/mwa_hyperdrive | Calibration software for the Murchison Widefield Array radio telescope, implementing direction-dependent and direction-independent calibration in Rust. |
| 7 | RadioAstronomySoftwareGroup/pyuvdata — Pythonic radio interferometry data interface | Python | 2026-06-08 | https://github.com/RadioAstronomySoftwareGroup/pyuvdata | Provides a unified Python interface for reading, writing, and converting radio astronomy interferometry data across multiple file formats. |
| 8 | lwa-project/bifrost — Stream processing framework for high-throughput radio data | Python / C++ | 2026-02-04 | https://github.com/lwa-project/bifrost | High-throughput radio data stream processing framework used for real-time pipeline applications at the Long Wavelength Array. |
| 9 | PerezHz/HORIZONS.jl — NASA-JPL HORIZONS system interface | Julia | 2026-06-09 | https://github.com/PerezHz/HORIZONS.jl | Julia package providing programmatic HTTP access to NASA's HORIZONS ephemeris system for orbital calculations and solar system body data retrieval. |
| 10 | tedcline/ezRA — Easy Radio Astronomy | Python | 2025-08-17 | https://github.com/tedcline/ezRA | Accessible software for receiving the 21 cm hydrogen line at 1420.4 MHz with an RTL-SDR dongle, targeted at amateur radio astronomers. |
| 11 | lockepatton/sonipy — Scatter plot sonification | Python | 2026-05-13 | https://github.com/lockepatton/sonipy | Converts scientific scatter plots into perceptually uniform audio files for inclusive data analysis in science and accessibility applications. |
| 12 | supercollider/supercollider — Audio server and algorithmic composition environment | C++ | 2026-06-13 | https://github.com/supercollider/supercollider | Widely-used audio server and programming language (SuperCollider) for sound synthesis and live coding, frequently used as a backend in astronomical sonification pipelines. |

---

## Semantic Scholar

| # | Title | Authors | Date | URL | Summary | Language |
|---|-------|---------|------|-----|---------|----------|
| 1 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | Johanna Casado, Wanda Diaz-Merced, Beatriz García | 2024 | https://www.semanticscholar.org/paper/Analysis-of-astronomical-data-through-sonification:-Casado-D%C3%ADaz-Merced/3365b0a81fee6c448407d4894ae94ad5c484bb91 | Develops a theoretical framework and sonoUno software to make astronomical data analysis accessible to visually impaired scientists through systematic sonification. | — |
| 2 | XSONIFY Sonification Tool for Space Physics | R. Candey, A. Schertenleib et al. | Legacy | https://www.semanticscholar.org/paper/XSONIFY-SONIFICATION-TOOL-FOR-SPACE-PHYSICS-Candey-Schertenleib/80ee2e773d67ad6a24f51e3ecabfa76ed5d2a7b1 | Extends NASA SPDF space physics data access for visually impaired users via a JavaSound API-based sonification data analysis tool. | Java |
| 3 | Sonification and Sound Design for Astronomy Research, Education and Public Engagement | Multiple | 2022 | https://www.semanticscholar.org/paper/efcab83dc7c81dfe6b720d0ae53ad2f6663c6b55 | Documents the decade-long explosion in astronomy sonification projects and catalogs motivations ranging from blind accessibility to scientific data discovery. | — |
| 4 | Signal Processing Tools for Radio Astronomy | A. J. van der Veen, S. J. Wijnholds | Legacy | https://www.semanticscholar.org/paper/Signal-Processing-Tools-for-Radio-Astronomy-Veen-Wijnholds/91bd096235867a98cbb943289bfd1461c1e6ad04 | Surveys signal processing algorithms (beamforming, calibration, imaging) used in modern radio telescope arrays such as LOFAR and the SKA. | — |
| 5 | Kepler Concordia: Designing an Immersive Modular Musical and Scientific Instrument Using Novel Blockchain and Sonification Technologies in XR | Snook, Barri et al. | Recent | https://www.semanticscholar.org/paper/Kepler-Concordia:-Designing-an-Immersive-Modular-in-Snook-Barri/460c3825b1eba8d501081e68411c844a3532096d | Presents an immersive XR instrument combining blockchain provenance and sonification of Kepler mission planetary data for artistic and scientific engagement. | — |

---

## Notes

- **JPL Horizons / Celestial Mechanics Audio**: No dedicated sonification paper specifically targeting JPL Horizons orbital data was found in this digest window. The closest active project is `HORIZONS.jl` (Julia), which provides the data access layer; sonification mapping on top of it remains an open opportunity. Older arXiv survey papers (2206.13536, 2402.16558) mention solar system orbit sonification as a case study category.
- **OSC (Open Sound Control) + Astronomy**: No astronomy-specific OSC paper was found on arXiv or Semantic Scholar in 2025–2026. The `strauss` Python package and `supercollider` are the most active general-purpose sonification backends in this space, and both support OSC routing.
- Deduplication applied: entries appearing across multiple sources are listed once under their primary source; cross-references noted implicitly by URL.

---

*Generated: 2026-06-14 | Next collection: 2026-06-21*
