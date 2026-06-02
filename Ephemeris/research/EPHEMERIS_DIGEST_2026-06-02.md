# EPHEMERIS DIGEST — 2026-06-02

Research digest on **radio astronomy**, **sonification**, and **space data**.
Search topics: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy.

---

## arXiv

| # | Title | Authors | Date | URL | Summary | Lang |
|---|-------|---------|------|-----|---------|------|
| 1 | **Exploring blazars through sonification: Visual and auditory insights into multifrequency variability** | Gustavo Magallanes-Guijón, Sergio Mendoza | 2025-02-04 (v3: 2026-03-04) | https://arxiv.org/abs/2502.01929 | Converts multi-frequency blazar light-curve data into sound using MIDI and parameter-mapping sonification to reveal variability patterns across the electromagnetic spectrum. | — |
| 2 | **STRAUSS: Sonification Tools & Resources for Analysis Using Sound Synthesis** | James W. Trayford et al. | 2025-04-02 | https://arxiv.org/abs/2504.01660 | Presents STRAUSS, a free open-source Python package that maps scientific datasets to audio, designed as a low-barrier "sonification pipeline" analogous to a plotting workflow. | Python |
| 3 | **herakoi: a sonification experiment for astronomical data** | Michele Ginolfi, Luca Di Mascolo, Anita Zanella | 2024-12-12 | https://arxiv.org/abs/2412.09152 | Introduces an open-source tool that converts astronomical images to sound in real time using a machine-learning hand-tracking interface via a standard webcam. | — |
| 4 | **EphemerisSources.jl: Idiomatic Ephemeris Sourcing and Parsing in Julia** | Joseph D. Carpinelli | 2024-11-19 | https://arxiv.org/abs/2411.12774 | Provides Julia packages for downloading and parsing Cartesian state-vector data from JPL ephemeris sources (Horizons, SPICE/CSPICE), enabling idiomatic celestial mechanics workflows. | Julia, C (CSPICE) |
| 5 | **Observations of the 21 cm HI Line from the Milky Way using Pyramidal Horn Radio Telescope** | Kaustav Bhattacharjee, Himanshu Grover, P. Arumugam | 2025-12-22 | https://arxiv.org/abs/2512.19262 | Designs and operates a low-cost pyramidal horn radio telescope with an SDR backend to detect Galactic neutral hydrogen at 1.42 GHz and map the Milky Way's rotation curve. | — (SDR pipeline) |
| 6 | **Galactic Neutral Hydrogen Structures: Designing a Home Radio Telescope for 21 cm Emission** | Jack Phelps | 2024-10-29 | https://arxiv.org/abs/2411.00057 | Describes a sub-$200 amateur radio telescope (1-m dish + H1-LNA + SDR + Raspberry Pi) capable of detecting the hydrogen line and generating Galactic velocity profiles. | Python (implied), SDR |
| 7 | **Sound training platform applied to astronomy** | Natasha Bertaina Lucero, Johanna Casado, Beatriz García, Gonzalo Cayo | 2024-05-09 | https://arxiv.org/abs/2405.06042 | Proposes a structured training platform so researchers can rigorously approach, understand, and analyse astronomical data through audio-based representation. | — |
| 8 | **A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response** | Kimberly K. Arcand et al. | 2024-03-26 | https://arxiv.org/abs/2403.18082 | Surveys 3,000+ participants on comprehension and accessibility of NASA telescope sonifications, showing improvements for blind, low-vision, and sighted audiences alike. | — |
| 9 | **Astronomical images sonification: inclusion or outreach?** | Johanna Casado, Beatriz García | 2024-02-01 | https://arxiv.org/abs/2402.00952 | Examines whether astronomical sonification tools (e.g., sonoUno) primarily serve outreach goals or function as genuine scientific research instruments. | — |
| 10 | **Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists** | Johanna Casado, Wanda Díaz-Merced, Beatriz García | 2024-02-01 | https://arxiv.org/abs/2402.00611 | Presents the sonoUno software framework and a theoretical accessibility model for enabling visually impaired scientists to analyse astronomical datasets via sonification. | — |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | **Listen to This Month's "Planetary Parade" with NASA's Chandra** | 2026-02-25 | https://chandra.harvard.edu/photo/2026/sonify11/ | Three sonifications map Chandra X-ray data (plus Hubble, Cassini, Keck optical data) for Jupiter, Saturn, and Uranus into distinct soundscapes timed to coincide with a rare six-planet alignment. |
| 2 | **NASA Data Sonifications** (ongoing collection — Chandra, Hubble, Webb) | Ongoing | https://www.nasa.gov/data-sonifications/ | Central NASA portal hosting 20+ sonifications of Chandra, Hubble, and Webb telescope observations, translating brightness, position, and spectral data to pitch, volume, and timbre. |
| 3 | **NASA Open Science: Astronomy Data Sonification** | Ongoing | https://science.nasa.gov/open-science/astronomy-data-sonification/ | Documents NASA's institutional commitment to converting multi-wavelength telescope data into audio, with open datasets and accessibility guides for the blind and low-vision community. |
| 4 | **Hubble Sonifications Collection** | Ongoing | https://science.nasa.gov/mission/hubble/multimedia/sonifications/ | Hubble-specific sonification gallery that maps nebular structure, star clusters, and galaxy imagery to musical notes and instruments; also hosts the interactive *Hearing Hubble* tool. |
| 5 | **NASA SPDF Sonification Research** | Ongoing | https://spdf.gsfc.nasa.gov/research/sonification/ | Space Physics Data Facility research page on translating in-situ plasma and magnetospheric data streams into audio for exploratory analysis. |

---

## GitHub

| # | Repository | Lang | Updated | URL | Summary |
|---|------------|------|---------|-----|---------|
| 1 | **james-trayford/strauss** — *Sonification Tools and Resources for Analysis Using Sound Synthesis* | Python | 2025-04-15 | https://github.com/james-trayford/strauss | Open-source Python sonification pipeline (JOSS 2025) enabling flexible, customisable audio rendering of scientific datasets; supports astronomy, climate science, and beyond. |
| 2 | **spacetelescope/astronify** — *Astronomical data sonification* | Python / Jupyter | Active | https://github.com/spacetelescope/astronify | STScI package for sonifying MAST archive light curves by mapping flux to pitch and time to note duration, aimed at accessibility and exploratory analysis. |
| 3 | **lockepatton/sonipy** — *Sonification tool for scatter plots* | Python | Active | https://github.com/lockepatton/sonipy | Converts scatter-plot data into perceptually uniform audio files by mapping y-values to pitch and x-values to timing, developed for the TransientZoo supernova citizen-science programme. |
| 4 | **evanmayer/rtlobs** — *RTL-SDR radio astronomy observation software* | Python / Jupyter | Active | https://github.com/evanmayer/rtlobs | Turns an inexpensive RTL-SDR dongle into a functional radio telescope supporting total-power integration, 21 cm hydrogen-line spectra, and frequency-switched bandpass calibration. |
| 5 | **spectregrams/spectre** — *SDR radio signal recorder & spectrogram tool* | Python | 2026-05-30 | https://github.com/spectregrams/spectre | Records radio signals and generates spectrograms from SDR devices with a focus on reproducible, file-based data collection for amateur and research radio astronomy. |
| 6 | **RadioAstronomySoftwareGroup/pyuvdata** — *Pythonic radio interferometry data interface* | Python | 2026-06-01 | https://github.com/RadioAstronomySoftwareGroup/pyuvdata | Provides a unified Python API for reading, writing, and converting radio interferometry visibility data across multiple file formats (UVFITS, MIRIAD, UVH5, etc.). |
| 7 | **WVURAIL/gr-radio_astro** — *GNUradio OOT modules for radio astronomy* | Python | 2025-08-28 | https://github.com/WVURAIL/gr-radio_astro | GNUradio out-of-tree blocks enabling real-time radio astronomy observations with SDR hardware, including hydrogen-line and pulsar detection workflows. |
| 8 | **lwa-project/bifrost** — *Stream processing for radio astronomy* | Python | 2026-02-04 | https://github.com/lwa-project/bifrost | High-throughput GPU-accelerated data-stream processing framework used by the Long Wavelength Array for real-time radio astronomy pipelines. |

---

## Semantic Scholar

*Note: Most Semantic Scholar results for these topics cross-index papers already listed under arXiv. The entry below is the primary Semantic Scholar record for the most-cited paper in this digest.*

| # | Title | Authors | Date | URL | Summary |
|---|-------|---------|------|-----|---------|
| 1 | **Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists** | Johanna Casado, Wanda Díaz-Merced, Beatriz García | 2024-02-01 | https://www.semanticscholar.org/paper/Analysis-of-astronomical-data-through-sonification:-Casado-D%C3%ADaz-Merced/3365b0a81fee6c448407d4894ae94ad5c484bb91 | Semantic Scholar record for the sonoUno accessibility framework paper (see also arXiv:2402.00611); cross-references related works including *astronify*, *strauss*, and the Audible Universe workshop proceedings. |

---

## Notes

- **Deduplication**: Papers appearing on both arXiv and Semantic Scholar are listed once under arXiv; the Semantic Scholar section retains only entries not otherwise captured.
- **OSC / Open Sound Control**: No dedicated astronomy+OSC papers were found in this search cycle. General OSC infrastructure projects exist (see [opensoundcontrol.stanford.edu](https://opensoundcontrol.stanford.edu/index.html)) but none specifically target astronomical data pipelines at time of writing.
- **JPL Horizons audio mapping**: No papers directly combine JPL Horizons ephemeris queries with audio/sonification output were found; the closest adjacent work is *EphemerisSources.jl* (arXiv:2411.12774) for data sourcing, and the Chandra Planetary Parade (2026-02-25) for celestial-mechanics-inspired audio.
- **RTL-SDR + sonification intersection**: No papers specifically combining RTL-SDR hardware with sonification output were indexed; RTL-SDR work remains focused on spectral detection and mapping rather than audio rendering.

---

*Generated: 2026-06-02 | Sources: arXiv, NASA, GitHub, Semantic Scholar*
