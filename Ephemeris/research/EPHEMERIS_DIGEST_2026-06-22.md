# EPHEMERIS DIGEST — 2026-06-22

> Automated research digest covering sonification, radio astronomy, and space data projects.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> This run surfaces items **not already present** in any prior digest (cross-checked against 279 previously recorded URLs spanning 2026-05-29 through 2026-06-21).

---

## arXiv

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | Unlocking the hidden potential of pulsar astronomy | 2025-06 | https://arxiv.org/html/2506.08056v1 | Review of non-traditional applications of pulsar astronomy (timing, navigation, space weather), noting amateur RTL-SDR-based pulsar detection efforts. | RTL-SDR (referenced) |
| 2 | The Completely Hackable Amateur Radio Telescope (CHART) Project | 2023-07 | https://arxiv.org/abs/2307.11173 | Describes an open, hackable, low-cost amateur radio telescope platform built for educational radio astronomy. | — |
| 3 | A Bose Horn Antenna Radio Telescope (BHARAT) design for 21 cm hydrogen line experiments for radio astronomy teaching | 2022-08 | https://arxiv.org/abs/2208.06070 | Presents a low-cost dual-mode conical horn-antenna radio telescope for teaching 21 cm hydrogen-line radio astronomy. | — |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | Sounds of Saturn: Hear Radio Emissions of the Planet and Its Moon Enceladus (JPL video) | Cassini-era (newly surfaced this run) | https://www.jpl.nasa.gov/videos/sounds-of-saturn-hear-radio-emissions-of-the-planet-and-its-moon-enceladus/ | Cassini plasma-wave radio recordings converted to audio, depicting the electromagnetic interaction between Saturn and Enceladus. |
| 2 | Listen: Sound of Electromagnetic Energy Moving Between Saturn, Enceladus | Cassini-era (companion piece, newly surfaced this run) | https://solarsystem.nasa.gov/news/487/listen-sound-of-electromagnetic-energy-moving-between-saturn-enceladus/ | Companion article on Cassini's final-orbit plasma-wave audio recording of the Saturn–Enceladus interaction. |
| 3 | Citizen Science — The Radio JOVE Project | Active, last modified 2024-08-02 | https://radiojove.gsfc.nasa.gov/citizen_science/ | Describes how Radio JOVE volunteers build and operate single-frequency radio telescopes and contribute heliophysics observations of the Sun, Jupiter, and the galaxy. |
| 4 | Horizons API documentation (JPL Solar System Dynamics) | Active reference, newly indexed this run | https://ssd-api.jpl.nasa.gov/doc/horizons.html | Official API documentation for programmatic access to JPL Horizons ephemeris data — a direct "JPL Horizons data mapping" reference resource. |
| 5 | Eyes on the Solar System (JPL) | Ongoing (relaunched ~2023) | https://eyes.nasa.gov/apps/solar-system/ | JPL's real-time 3D visualization tool rendering planet and spacecraft positions, conceptually adjacent to Horizons ephemeris data mapping. |
| 6 | Sounds from Beyond | Last updated 2025-06-10 | https://www.nasa.gov/sounds-from-beyond/ | NASA mission-audio collection hub spanning Perseverance, InSight, Juno (Jupiter radio emissions), and the Artemis I launch. |

---

## GitHub

| # | Repository | Created/Updated | URL | Summary | Language |
|---|-----------|------------------|-----|---------|----------|
| 1 | JuliaAstro/EphemerisSources.jl | Updated 21 hours ago | https://github.com/JuliaAstro/EphemerisSources.jl | Idiomatic Julia package providing access to JPL HORIZONS and SPICE ephemeris sources. | Julia |
| 2 | OliRalph96/jpl-horizons-sandbox | Updated 19 days ago | https://github.com/OliRalph96/jpl-horizons-sandbox | Experimentation platform for working with JPL Horizons ephemeris datasets. | Python |
| 3 | SergheiBrinza/1420MHz-Feed-Horn | Updated Apr 24 | https://github.com/SergheiBrinza/1420MHz-Feed-Horn | Feed-horn antenna design for 1420 MHz hydrogen-line radio astronomy observations. | — |
| 4 | mattjhawken/deepfield | Updated May 8 | https://github.com/mattjhawken/deepfield | Distributed radio telescope array/network for collaborative hydrogen-line interferometry. | Python |
| 5 | mtang724/uconsole-hline | Updated Apr 10 | https://github.com/mtang724/uconsole-hline | Hydrogen-line radio astronomy on the ClockworkPi uConsole using GNU Radio and SDR++ pipelines. | Python |
| 6 | astrlus/Sphere-sonif | Updated Dec 27, 2025 | https://github.com/astrlus/Sphere-sonif | Converts astrophotographs into sound, inspired by NASA's official sonification releases. | Jupyter Notebook |
| 7 | CaptainGG/Astroid-Soundscape | Updated Feb 2 | https://github.com/CaptainGG/Astroid-Soundscape | Visualization and sonification of NASA Near-Earth Object (NEO) data. | JavaScript |
| 8 | dewiweb/spacemouse-osc | Updated Mar 13 | https://github.com/dewiweb/spacemouse-osc | Open Sound Control (OSC) bridge for the 3Dconnexion SpaceMouse Compact 6-DOF spatial input device — not astronomy-specific, but the closest direct OSC-protocol match found this run. | JavaScript |
| 9 | yannherren/hydrogen-line-observations | Updated Aug 28, 2025 | https://github.com/yannherren/hydrogen-line-observations | Amateur radio astronomy experiment detecting the galactic 21 cm HI line via SDRangel. | Jupyter Notebook |
| 10 | AuditoryVO/DVT-Explorer | Older, newly surfaced this run | https://github.com/AuditoryVO/DVT-Explorer | Sonification of star/planet variables from TESS Data Validation Time-series files. | — |

**Excluded as self-referential:** a GitHub search hit returned `omgyjyaswitch7/ephemeris` itself (this digest's own repository) — omitted from results above.

---

## Semantic Scholar

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | OpenSpace Sonification: Complementing Visualization of the Solar System with Sound | 2021 | https://repository.gatech.edu/entities/publication/d987fa85-061b-4750-9e7a-70c84b9f43b3 | User-centered design work adding sonification of planetary size and orbital period to the OpenSpace visualization software for planetarium use — a direct "celestial mechanics audio" match. | OpenSpace (C++) |
| 2 | A Bose Horn Antenna Radio Telescope (BHARAT) design for 21 cm hydrogen line experiments for radio astronomy teaching | 2022-08 | https://www.semanticscholar.org/paper/18e1350bd65aa70720b9a7f08fc3c250419e6de9 | Same paper as the arXiv entry above (2208.06070), surfaced independently via Semantic Scholar — listed once in the arXiv section to avoid duplication. | — |
| 3 | Design and Implementation of a Software Defined Radio-Based Radio Telescope for Hydrogen Line Observation at 1.42 GHz | 2024-03 | https://www.researchgate.net/publication/378880293 | Builds an RTL-SDR-based hydrogen-line radio telescope using SDRSharp with an IF Average plugin to extract the 21 cm signal from noise. | RTL-SDR / SDRSharp |
| 4 | Synthetic Pulsar | 2022 | https://2022.xcoax.org/pdf/xcoax2022-pietruszewski.pdf | Speculative-sonification artwork/research amplifying European Pulsar Network data through "nuPG," a pulsar-synthesis sound generator. | SuperCollider 3 |
| 5 | Sound Composition with Pulsars | 2001 | https://www.semanticscholar.org/paper/a71ba8d931373ca5db9e7cf5a7d0c2ccfffd2684 | Curtis Roads's foundational paper on "pulsar synthesis," an electronic-music technique generating sonic particle trains, named after and inspired by astrophysical pulsars. | — |
| 6 | Lend Me Your Ears: Space Weather Citizen Science Through Harnessing Sonification | 2023 | https://ui.adsabs.harvard.edu/abs/2023EGUGA..2513888A/abstract | Presents sonification tools rendering magnetospheric ULF wave data audible for citizen-science engagement, part of the MUSICS project. | — |
| 7 | First results from sonification and exploratory citizen science of magnetospheric ULF waves | 2018 | https://arxiv.org/abs/1811.02816 | Early MUSICS project paper sonifying decreasing-frequency poloidal field-line resonances following geomagnetic storms for citizen scientists. | — |

---

## Notes

- **OSC / Open Sound Control + Astronomy**: Still no dedicated arXiv, Semantic Scholar, NASA, or GitHub item found combining the OSC protocol with astronomy specifically. `dewiweb/spacemouse-osc` (GitHub, item 8 above) is the closest OSC-protocol match this run, but it is a general spatial-input bridge, not astronomy-specific — the gap noted in every prior digest persists.
- **JPL Horizons + Audio**: No new item pairs Horizons ephemeris data directly with audio/sonification output. This run's Horizons-related finds (`EphemerisSources.jl`, `jpl-horizons-sandbox`, the Horizons API docs page, Eyes on the Solar System) are all data-access or visualization tools, not audio pipelines.
- **RTL-SDR Radio Astronomy**: Several new hydrogen-line/RTL-SDR builds surfaced (GitHub items 3–5, 9; Semantic Scholar item 3), continuing the steady stream of amateur 21 cm radio-telescope projects — still no project found that combines RTL-SDR output directly with sonification/audio rendering.
- **Semantic Scholar**: Two MUSICS-project papers (2018, 2023) and two pulsar-sonification works (2001, 2022) were newly catalogued this run, beyond the previously-recorded STRAUSS/sonoUno/Edukoi/Herakoi cluster.
- All entries deduplicated by URL and title against this digest and all 23 prior digests in `Ephemeris/research/` and `research/` (279 previously recorded URLs).

---

*Generated by automated research routine · 2026-06-22*
