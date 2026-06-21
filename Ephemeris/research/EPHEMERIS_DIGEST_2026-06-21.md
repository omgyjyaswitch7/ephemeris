# EPHEMERIS DIGEST — 2026-06-21

> Automated research digest covering sonification, radio astronomy, and space data projects.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> This run surfaces items **not already present** in any prior digest (cross-checked against 266 previously recorded URLs spanning 2026-05-29 through 2026-06-20).

---

## arXiv

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | Barycentric Corrections for HST/STIS Data (`stistools.barycentric_correction`) | 2026-06-10 | https://arxiv.org/abs/2606.12244 | New utility that computes HST barycentric timing corrections by querying JPL Horizons directly for spacecraft position, replacing the deprecated IRAF `odelaytime` task and separate ephemeris-file downloads — a concrete "JPL Horizons data mapping" example. | Python (astropy) |
| 2 | A High-Likelihood Polar Interstellar Meteor Candidate | 2026-06-03 | https://arxiv.org/abs/2606.04379 | Identifies a candidate interstellar meteor by converting an Earth-fixed velocity vector to a heliocentric orbit using JPL Horizons' heliocentric Earth velocity, then testing it against solar escape speed. | — |
| 3 | Open-Source High-Fidelity Orbit Estimation for Planetary Science and SSA Using the Tudat Software | 2025-10-27 | https://arxiv.org/abs/2510.23179 | Describes Tudat (TU Delft Astrodynamics Toolbox), an open-source suite for orbit estimation and astrodynamics research combining optical/radiometric tracking data, interoperable with JPL ephemerides. | C++ (Python bindings via tudatpy) |
| 4 | A High-Precision, Differentiable Code for Solar System Ephemerides (`jorbit`) | 2025-09-23 | https://arxiv.org/abs/2509.19549 | Presents jorbit, a JAX-based, auto-differentiable, GPU-capable library that parses JPL DE-series ephemerides and matches JPL Horizons to ~1 mas over decade timescales for asteroid orbit work. | Python/JAX |
| 5 | Simultaneous Double Transits of Phobos and Deimos as Seen from the Martian Surface | 2026-02-19 | https://arxiv.org/abs/2602.18513 | Uses the JPL mar099 ephemeris and SPICE toolkit to catalogue 8,500+ years (1600–2600 CE) of double solar transits of Mars's two moons. | — (SPICE toolkit) |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | Radio JOVE Volunteers Tune In to the Sun's Low Notes | 2025-07-23 | https://science.nasa.gov/science-research/heliophysics/radio-jove-volunteers-tune-in-to-the-suns-low-notes/ | NASA citizen-science Radio JOVE participants report a growing number of Type II solar radio bursts detected at unusually low frequencies (15–30 MHz, between the FM and AM bands) during the current solar active cycle. |

---

## GitHub

| # | Repository | Created/Updated | URL | Summary | Language |
|---|-----------|------------------|-----|---------|----------|
| 1 | stevenmctang/universe-sonification | 2026-06-15 / pushed 2026-06-16 | https://github.com/stevenmctang/universe-sonification | Cloud-built, open-source interactive web platform turning raw astronomical and environmental data streams into "cinematic" auditory soundscapes. | JavaScript |
| 2 | alessandrofiordelmondo/sonificazionelunare | 2026-06-12 | https://github.com/alessandrofiordelmondo/sonificazionelunare | "Sonificazione Lunare" — a sound installation that sonifies real-time astronomical data about the Moon. | Python |
| 3 | KevinWeiss1995/Orbitals | 2026-06-19 | https://github.com/KevinWeiss1995/Orbitals | Zero-dependency, real-time macOS dynamical-systems engine pairing Metal-accelerated chaos visualization with algorithmic harmonic sonification. | Objective-C++ |
| 4 | iiAdLeR/ai-star-composer | 2026-06-14 | https://github.com/iiAdLeR/ai-star-composer | Graduation project sonifying NASA orbital data using an LSTM model behind a FastAPI backend and React frontend. | TypeScript / Python (FastAPI) |
| 5 | ferfava/Blue-Sphere-Orbital-Language | created 2026-04-19, pushed 2026-05-03 | https://github.com/ferfava/Blue-Sphere-Orbital-Language | Applies NLP techniques to satellite telemetry, treating orbital data as a linguistic corpus to drive "semantic" sonification. | Python |
| 6 | gue-ni/RadioHeatmap | 2019 (newly surfaced this run) | https://github.com/gue-ni/RadioHeatmap | RF heatmap-generation tool explicitly tagged `astronomy` and `rtl-sdr` on GitHub — older project, included as a direct RTL-SDR/radio-astronomy topic match not previously catalogued. | Java |
| 7 | xavi520/Pulsar-Data-Sonification | 2024-11-13 (newly surfaced this run) | https://github.com/xavi520/Pulsar-Data-Sonification | Minimal repository titled "Pulsar Data Sonification"; no README/description beyond the title and no detected source language. | — |

---

## Semantic Scholar

No genuinely new Semantic Scholar entries were found this run — every result returned by searches across all eight topics (sonification astronomy, radio astronomy sound data, astronomical data sonification, JPL Horizons data mapping, space data audio visualization, OSC astronomy, celestial mechanics audio, RTL-SDR radio astronomy) resolved to papers already catalogued in prior digests (e.g. STRAUSS, sonoUno family, Edukoi, "Open Your Ears and Take a Look," "A Universe of Sound" participant-response study).

---

## Notes

- **OSC / Open Sound Control + Astronomy**: Still no dedicated arXiv, Semantic Scholar, NASA, or GitHub item found combining the OSC protocol with astronomy specifically — confirms the gap noted in every prior digest.
- **JPL Horizons + Audio**: Five new arXiv items use JPL Horizons/JPL ephemerides this run, but all are positional/orbital-data tools or science results — none pair Horizons data with an audio/sonification output. The standing closest audio-adjacent match remains `JOnathanST29/artemis2-live` (visual tracker, recorded in the 2026-06-20 digest).
- **RTL-SDR Radio Astronomy**: One older repo (`gue-ni/RadioHeatmap`, 2019) newly surfaced via topic-tag search; still no project found that combines RTL-SDR output directly with sonification/audio rendering.
- **Semantic Scholar**: No new papers this run — see dedicated section above.
- All entries deduplicated by URL and title against this digest and all 17 prior digests in `Ephemeris/research/` and `research/`.

---

*Generated by automated research routine · 2026-06-21*
