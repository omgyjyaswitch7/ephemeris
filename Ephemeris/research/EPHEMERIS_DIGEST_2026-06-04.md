# EPHEMERIS DIGEST — 2026-06-04

**Topics searched:** sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy  
**Sources queried:** arXiv · NASA · GitHub · Semantic Scholar

---

## arXiv

| # | Title | Date | Summary | Language | URL |
|---|-------|------|---------|----------|-----|
| 1 | **What does the Universe sound like?** | 2026-04-01 | Converts gravitational-wave data from ~10⁶ synthetic compact binary coalescence events into audio, producing a low-frequency rumble that serves as a novel sonification of the gravitational-wave universe. | — | https://arxiv.org/abs/2603.29996 |
| 2 | **Preliminary sonification of ENSO using traditional Javanese gamelan scales** | 2026-02-16 | Converts El Niño-Southern Oscillation climate data into audio using Indonesian gamelan scales and evaluates whether the sonification preserves the system's dynamical characteristics via phase-space analysis. | — | https://arxiv.org/abs/2602.14560 |
| 3 | **Exploring blazars through sonification: Visual and auditory insights into multifrequency variability** | 2025-02-04 (rev. 2026-03-04) | Applies MIDI-based Parameter Mapping Sonification (PMSon) to multi-frequency light curves of nine blazars, showing that auditory representations reveal variability patterns comparable to visual analysis. | MIDI / PMSon | https://arxiv.org/abs/2502.01929 |
| 4 | **STRAUSS: Sonification Tools & Resources for Analysis Using Sound Synthesis** | 2025-04-02 | Introduces a flexible, fully open-source Python package that provides a complete pipeline from scientific data to sonified audio, targeting research and education across multiple domains. | **Python** | https://arxiv.org/abs/2504.01660 |
| 5 | **herakoi: a sonification experiment for astronomical data** | 2024-12-12 | Open-source software using ML-based real-time hand tracking via webcam to map spatial positions on astronomical images to sound parameters, enabling interactive sonification without specialist hardware. | Python (ML) | https://arxiv.org/abs/2412.09152 |
| 6 | **A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response** | 2024-03-26 | Converts Chandra/JWST/Hubble data into audio representations and measures how blind/low-vision and sighted participants perceive and engage with the resulting sonifications. | — | https://arxiv.org/abs/2403.18082 |
| 7 | **Astronomical images sonification: inclusion or outreach?** | 2024-02-01 | Critiques existing astronomical sonification projects and argues for moving beyond outreach towards genuine research inclusion for scientists with visual impairments. | — | https://arxiv.org/abs/2402.00952 |
| 8 | **Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists** | 2024-02-01 | Presents the sonoUno software framework and a theoretical model for enabling visually impaired researchers to independently analyse astronomical datasets through sonification. | — | https://arxiv.org/abs/2402.00611 |
| 9 | **Sound training platform applied to astronomy** | 2024-05-09 | Describes a training platform converting astronomical visual data into auditory and tactile displays to foster more inclusive, multisensory participation in space science. | — | https://arxiv.org/abs/2405.06042 |
| 10 | **Sonification and Sound Design for Astronomy Research, Education and Public Engagement** | 2022-06 | Comprehensive review of methodologies and tools for translating astronomical data into sound, establishing guidelines for the Audible Universe community of practice. | — | https://arxiv.org/abs/2206.13536 |

---

## NASA

| # | Title | Date | Summary | URL |
|---|-------|------|---------|-----|
| 1 | **NASA Telescopes Tune Into a Black Hole Prelude, Fugue** | 2025-05 | Three new sonifications of Chandra/JWST/IXPE data representing WR124 (Wolf-Rayet star), SS 433 (binary compact-object system), and Centaurus A (relativistic jet), each mapped to distinct instrumental timbres. | https://www.nasa.gov/missions/chandra/nasa-telescopes-tune-into-a-black-hole-prelude-fugue/ |
| 2 | **Little Red Dot Abell2744-QSO1: Sonification of Gas Velocity Around a Supermassive Black Hole** | 2025 | Webb NIRCam/NIRSpec IFU data of a high-redshift AGN translated so that hydrogen gas velocity relative to the central black hole maps to audio pitch, directly encoding kinematic structure as sound. | https://science.nasa.gov/asset/webb/little-red-dot-abell2744-qso1-sonification-of-gas-velocity-around-a-supermassive-black-hole-nircam-and-nirspec-ifu/ |
| 3 | **NASA Open Science Reveals Sounds of Space** | 2025 | Overview of NASA's astronomy sonification programme showing how the same digital data used for telescope images is transformed into sound with brightness and position mapped to pitch and volume. | https://science.nasa.gov/open-science/astronomy-data-sonification/ |
| 4 | **Data Sonifications — NASA** (collection, updated June 2025) | June 2025 | Central catalogue of all NASA-released sonifications from Hubble, Chandra, and JWST missions, each converting telescope data into layered audio representations for scientific and accessibility purposes. | https://www.nasa.gov/data-sonifications/ |
| 5 | **5,000 Exoplanets: Listen to the Sounds of Discovery** | — | Sonification of the cumulative exoplanet confirmation catalogue, mapping discovery timing and orbital parameters to musical notes to mark the 5,000th confirmed exoplanet milestone. | https://science.nasa.gov/resource/video-5000-exoplanets-listen-to-the-sounds-of-discovery-nasa-data-sonification/ |

---

## GitHub

| # | Repository | Language | Summary | URL |
|---|-----------|----------|---------|-----|
| 1 | **sesselastronaut/celestialBodyTracking** | JavaScript 79% · Python 19% | Tracks planets, satellites, space debris, comets, and ISS/Voyager using PyEphem ephemeris data, then converts positional parameters to real-time audio via the Web Audio API with mobile compass support. | https://github.com/sesselastronaut/celestialBodyTracking |
| 2 | **HSSBoston/constellation-sonifier** | **Python 100%** | 2024 3M Young Scientist Challenge finalist; extracts six constellation features (size, brightness, star colours) and maps them to five musical dimensions (melody, rhythm, harmony, dynamics, articulation) using GPS/IMU for real-time sky identification. | https://github.com/HSSBoston/constellation-sonifier |
| 3 | **evanmayer/rtlobs** | **Python** | RTL-SDR-based radio astronomy toolkit supporting total-power integration, 21 cm hydrogen line spectroscopy, and frequency-switched observation mode for bandpass flattening. | https://github.com/evanmayer/rtlobs |
| 4 | **jrcheshire/1420SDR** | **Python** | Python utilities specifically designed for 21 cm hydrogen line observations with RTL-SDR dongles, providing spectrometer and Doppler-shift measurement pipelines. | https://github.com/jermizzey/1420SDR |
| 5 | **TrevTron/rtl-ml** | **Python** | AI-powered radio signal classifier using RTL-SDR + ARM SBC (Raspberry Pi 5) that identifies FM, NOAA Weather, APRS, FRS/GMRS, and ISM sensor signals with 96.9% accuracy via a full capture→train→classify pipeline. | https://github.com/TrevTron/rtl-ml |
| 6 | **f4exb/sdrangel** (Radio Astronomy plugin) | C++ | Full-featured SDR Rx/Tx application with a dedicated Radio Astronomy plugin targeting 1420.405 MHz neutral hydrogen observations, compatible with RTL-SDR, HackRF, LimeSDR, and other hardware. | https://github.com/f4exb/sdrangel/blob/master/plugins/channelrx/radioastronomy/readme.md |
| 7 | **ninaspitfire/OpenSpaceKontrol** | — | Provides real-time telemetry and remote control for Kerbal Space Program vessels over UDP using the Open Sound Control (OSC) protocol, bridging space simulation with any OSC-capable audio/control software. | https://github.com/ninaspitfire/OpenSpaceKontrol |

---

## Semantic Scholar

*(Papers cross-indexed here that were not deduplicated with arXiv entries above)*

| # | Title | Summary | URL |
|---|-------|---------|-----|
| 1 | **XSONIFY Sonification Tool for Space Physics** | Early NASA/GSFC tool for sonifying magnetospheric and heliophysics data streams, mapping parameters such as magnetic field magnitude and particle flux to audio in real time for scientific analysis. | https://www.semanticscholar.org/paper/XSONIFY-SONIFICATION-TOOL-FOR-SPACE-PHYSICS-Candey-Schertenleib/80ee2e773d67ad6a24f51e3ecabfa76ed5d2a7b1 |
| 2 | **Web Sonification Sandbox: An Easy-to-Use Web Application for Sonifying Data and Equations** | Browser-based sandbox that allows users to upload arbitrary datasets or mathematical equations and convert them to audio using configurable parameter-mapping rules, lowering the barrier for domain scientists. | https://www.semanticscholar.org/paper/Web-Sonification-Sandbox-an-Easy-to-Use-Web-for-and-Kondak-Liang/6b27831d1e670ba7eaaacec619a984e06a008857 |

---

## Notes

- **JPL Horizons / OSC astronomy:** No dedicated papers or repositories directly combining JPL Horizons ephemeris API with OSC-based audio mapping were found in this search cycle. The `celestialBodyTracking` GitHub repo is the closest match, using PyEphem (a Horizons-compatible ephemeris library) with Web Audio API. This remains a gap worth monitoring.
- **ENSO sonification** (arXiv 2602.14560) is not strictly astronomical but was included as it directly applies sonification methodology to geophysical time-series and cites the broader space-data community.
- All dates reflect submission/publication date or last known update; arXiv preprints may have later journal versions.
- Programming language noted only when explicitly stated or directly inferable from the repository/paper.

---

*Digest generated: 2026-06-04 | Next recommended update: 2026-07-04*
