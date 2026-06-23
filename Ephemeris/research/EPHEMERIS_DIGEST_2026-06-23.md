# EPHEMERIS DIGEST — 2026-06-23

> Automated research digest covering sonification, radio astronomy, and space data projects.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> This run surfaces items **not already present** in any prior digest (cross-checked against 305 previously recorded URLs spanning 2026-05-29 through 2026-06-22).

---

## arXiv

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | The interstellar signature: A computational framework for open source interstellar tracking | 2025-12 | https://arxiv.org/abs/2512.07910 | Web-based platform (NexusCosmos ecosystem) integrating public ephemeris/data repositories with physics-based simulations to render interstellar and solar-system object motion in real time — an ephemeris-to-3D coordinate mapping akin to JPL Horizons data mapping. | — |
| 2 | Blade Antenna-SDR System Prototype for the CANTAR Global 21-cm Experiment: Simulations, Measurements, and In-Situ Results | 2025-08 (v2 2025-12) | https://arxiv.org/abs/2508.18020 | Develops and field-tests a low-frequency (100–200 MHz) radio telescope prototype pairing a blade dipole antenna with an SDR receiver chain for 21 cm cosmology, evaluated across three SDR hardware platforms. | SDR (hardware-focused; no software language named) |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | Eerie Sounds of Saturn's Radio Emissions | 2005-07-25 | https://www.jpl.nasa.gov/images/pia07966-eerie-sounds-of-saturns-radio-emissions/ | JPL image/audio page converting Cassini-detected Saturn auroral radio emissions into audible "eerie sounds" via downward frequency shifting. |
| 2 | GAVRT — Goldstone Apple Valley Radio Telescope | Active reference, undated | https://science.jpl.nasa.gov/projects/gavrt/ | JPL/educational-partnership program letting K-12 students remotely operate a 34 m radio telescope for Jupiter, solar, black-hole, and SETI observations. |
| 3 | NASA Space Sounds API | Published 2015-11-30, last modified 2020-01-29 | https://data.nasa.gov/dataset/nasa-space-sounds-api | NASA Open Data Portal listing for a public API offering developer access to NASA's curated SoundCloud collection of space sounds. |
| 4 | Cassini Multimedia — Audio | Last updated 2024-11-02 | https://science.nasa.gov/mission/cassini/multimedia/audio?types=audio | Searchable, filterable archive of Cassini mission audio files. |
| 5 | The Sounds of Interstellar Space | 2013-10-31 | https://science.nasa.gov/science-research/planetary-science/01nov_ismsounds/ | Describes how Voyager 1's plasma wave instrument converted interstellar plasma oscillations into audible tones, confirming the heliosphere crossing. |
| 6 | Little Red Dot Abell2744-QSO1a (NIRCam Image with NIRSpec IFU Velocity Map) | 2026-05-27 | https://science.nasa.gov/asset/webb/little-red-dot-abell2744-qso1a-nircam-image-with-nirspec-ifu-velocity-map/ | Webb image/velocity-map asset page underlying a black-hole gas-velocity sonification dataset. |
| 7 | Sinister Sounds of the Solar System | 2020-10-28 | https://science.nasa.gov/resource/sinister-sounds-of-the-solar-system/ | Halloween-themed NASA playlist of "moans and whistles" compiled from spacecraft audio/sonification data. |
| 8 | Supernova 1987A Sonification | 2020-12-01 | https://science.nasa.gov/resource/supernova-1987a-sonification/ | Chandra X-ray and Hubble imaging data of Supernova 1987A sonified, mapping brightness to pitch and volume. |
| 9 | Sound of Saturn: Radio Emissions of the Planet and Enceladus | 2018-07-09 (updated 2023-09-27) | https://science.nasa.gov/resource/sound-of-saturn-radio-emissions-of-the-planet-and-enceladus/ | Cassini RPWS recording of the plasma-wave interaction between Saturn and Enceladus during the Grand Finale orbits, converted to an audible "whooshing" sound. |
| 10 | NASA's Cassini Listens to Eerie New Sounds of Space Near Jupiter | 2001-01-03 | https://science.nasa.gov/missions/cassini/nasas-cassini-listens-to-eerie-new-sounds-of-space-near-jupiter/ | Early Cassini flyby article describing low-frequency Jupiter radio waves converted to audio, likened to "howler monkeys battling underwater." |

---

## GitHub

| # | Repository | Created/Updated | URL | Summary | Language |
|---|-----------|------------------|-----|---------|----------|
| 1 | interTwin-eu/pulsar-plugin | Active, 2026 | https://github.com/interTwin-eu/pulsar-plugin | Radio-astronomy pulsar-detection plugin integrating ML models (UNet, FilterCNN, CNN1D) into the itwinai AI-pipeline library. | Python |
| 2 | stepankaiser/artemis-tracker | Built April 2026 | https://github.com/stepankaiser/artemis-tracker | Real-time LED-strip and phone-dashboard tracker for NASA's Artemis II spacecraft, driven by JPL Horizons telemetry. | Python |
| 3 | w00jay/artemisee | v0.3.2, Apr 6 2026 | https://github.com/w00jay/artemisee | Interactive 3D visualizer of Artemis mission trajectories (Orion, Earth, Moon, ISS) using real JPL Horizons data, with mission replay and space-weather feeds. | TypeScript |
| 4 | will-roscoe/nbody | Active | https://github.com/will-roscoe/nbody | N-body gravitational simulation library with JPL Horizons data integration for celestial mechanics visualization. | Python |
| 5 | staylor7/exoplanet-sonification | Newly surfaced this run | https://github.com/staylor7/exoplanet-sonification | Sonified chart of exoplanets mapping planet size to pitch and atmosphere composition to timbre, built with the Web Audio API. | HTML/JS (Web Audio API) |

**Excluded as self-referential:** `omgyjyaswitch7/ephemeris` (this digest's own repository).

---

## Semantic Scholar

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | Experiencing a Slice of the Sky: Immersive Rendering and Sonification of Antarctic Astronomy Data | 2018 | https://library.imaging.org/ei/articles/30/3/art00006 | Builds an immersive game-engine VR star field from 817,373 Antarctic AST3-telescope objects with ambisonic, granular-synthesis sonification for collaborative exploration. | — |
| 2 | The Audible Universe Workshop: An Interdisciplinary Approach to the Design and Evaluation of Tools for Astronomical Data Sonification | 2023-06 | https://hal.science/hal-04476321 | Reports outcomes of a 50-expert ICAD 2023 workshop bringing astronomers and sound designers together to consolidate and evaluate astronomical sonification tools. | — |
| 3 | Stellar Command: a planetarium software based cosmic performance interface | 2019 | https://www.nime.org/proceedings/2019/nime2019_paper075.pdf | Couples the Stellarium planetarium app with the VizieR star catalogue via **Open Sound Control** to drive a live musical performance interface — the first direct OSC + astronomy match found across all digest runs to date. | Java (HappyBrackets), OSC |
| 4 | Planethesizer: Approaching Exoplanet Sonification | 2018 | https://pdfs.semanticscholar.org/351d/69982e1ba6c8d534a6153ee53a0d9f869f93.pdf | Virtual interactive synthesizer mapping exoplanet light-curve flux variations (TRAPPIST-1, Kepler-444, K2-72) to musical synthesis parameters. | Custom software (Planethesizer) |
| 5 | AMACA: Astronomy education with a Multi-sensory, Accessible, and Circular Approach | 2026-01 | https://arxiv.org/abs/2601.13326 | Describes a circular educational program building multi-sensory, sonification-oriented astronomy activities with PhD students, teachers, and high schoolers for accessibility. | — |

---

## Notes

- **OSC / Open Sound Control + Astronomy — gap closed this run**: "Stellar Command" (Semantic Scholar item 3) is the first item found in any digest run that directly pairs the OSC protocol with an astronomy data source (Stellarium + VizieR catalogue data driving live performance). The persistent gap noted in every prior digest since 2026-05-29 is now resolved with a genuine match, though it remains a thin area — only one such item exists.
- **JPL Horizons + Audio**: Still no item pairs Horizons ephemeris data directly with an audio/sonification pipeline. This run's Horizons-related finds (`stepankaiser/artemis-tracker`, `w00jay/artemisee`, `will-roscoe/nbody`, the interstellar-tracking arXiv paper) are visualization/tracking tools, not audio output.
- **RTL-SDR Radio Astronomy**: One new SDR hardware paper (CANTAR 21-cm blade-antenna prototype) continues the steady stream of amateur/research-grade radio-telescope hardware work; still no project found that combines RTL-SDR output directly with sonification/audio rendering.
- **Exoplanet sonification**: Two new finds this run (`staylor7/exoplanet-sonification` on GitHub, "Planethesizer" on Semantic Scholar) — an emerging sub-cluster distinct from the previously catalogued pulsar- and magnetosphere-sonification work.
- All entries deduplicated by URL and title against this digest and all 24 prior digests in `Ephemeris/research/` and `research/` (305 previously recorded URLs). All new URLs in this digest were spot-verified for HTTP reachability before inclusion.

---

*Generated by automated research routine · 2026-06-23*
