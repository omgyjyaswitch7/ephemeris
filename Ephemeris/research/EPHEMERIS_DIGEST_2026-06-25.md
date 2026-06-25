# EPHEMERIS DIGEST — 2026-06-25

> Automated research digest covering sonification, radio astronomy, and space data projects.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> This run surfaces items **not already present** in any prior digest (cross-checked against 327 previously recorded URLs spanning 2026-05-29 through 2026-06-23).

---

## arXiv

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | The Sound of Noise: Leveraging the Inductive Bias of Pre-trained Audio Transformers for Glitch Identification in LIGO | 2026-01-27 | https://arxiv.org/abs/2601.20034 | Treats LIGO gravitational-wave strain data through the lens of audio processing, using a pre-trained Audio Spectrogram Transformer to identify detector noise glitches (including potential intermediate-mass black hole signals) without training from scratch. | — |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | Earth to Space: A National Symphony Orchestra Concert | Released 2025-03-28 | https://svs.gsfc.nasa.gov/14802/ | NASA Scientific Visualization Studio page pairing data visualizations (hurricanes, nebulas, black holes, exoplanets, magnetars, the Sun) with a National Symphony Orchestra concert performance. |
| 2 | NASA Goddard, National Philharmonic Explore Cosmos Through Imagery, Music Collaboration | 2023-05-15 | https://www.nasa.gov/centers-and-facilities/goddard/nasa-goddard-national-philharmonic-explore-cosmos-through-imagery-music-collaboration/ | Describes how NASA Goddard, the National Philharmonic, and composer Henry Dehlinger created "Cosmic Cycles: A Space Symphony," composing music to match pre-made NASA visualization footage. |
| 3 | Small Steps, Giant Leaps — Episode 160: Turning Space Data Into Sound | 2025-08-20 | https://www.nasa.gov/podcasts/small-steps-giant-leaps/small-steps-giant-leaps-episode-160-turning-space-data-into-sound/ | NASA podcast episode with Dr. Kimberly Arcand (Chandra/CfA) explaining how telescope data (position, brightness, energy) is sonified into pitch and instrumentation for accessibility and public engagement. |
| 4 | Exploring the Universe Through Sight, Touch, and Sound | 2025-04-14 | https://science.nasa.gov/learning-resources/science-activation/exploring-the-universe-through-sight-touch-and-sound/ | NASA's Universe of Learning page describing "Mini Stars 3D Kits" pairing 3D-printed celestial models with audio data-sonification files, distributed via Library of Congress hubs for multisensory accessibility. |
| 5 | Cosmic Cycles: A Space Symphony | Released 2023-03-15, updated 2023-04-28 | https://svs.gsfc.nasa.gov/gallery/cosmiccycles/ | NASA Goddard SVS gallery for a seven-movement multimedia symphony pairing original orchestral music with NASA visualizations spanning the Sun, Earth, Moon, planets, and deep space. |
| 6 | Cosmic Cycles 1: The Sun | Published 2023-05-11, updated 2023-05-09 | https://svs.gsfc.nasa.gov/14313 | First movement of NASA's "Cosmic Cycles" space symphony, pairing visuals of solar surface explosions and plasma loops with original orchestral music. |
| 7 | Sounds of the Sun | Updated 2023-07-26 | https://www.nasa.gov/solar-system/sounds-of-the-sun/ | NASA page explaining how SOHO data on solar vibrations is converted into audible sound to study internal solar dynamics not otherwise observable. |

---

## GitHub

| # | Repository | Created/Updated | URL | Summary | Language |
|---|-----------|------------------|-----|---------|----------|
| 1 | almita-radio/almita | Updated 2026-06-09 | https://github.com/almita-radio/almita | Amateur radio astronomy project automating 21 cm hydrogen-line (1420.405 MHz) observations using a Raspberry Pi 5, RTL-SDR V4, INDI/OnStep mount control, and HDF5 data storage with calibration and hydrogen-map generation. | Python |
| 2 | adhyanthac/h-line-radio-telescope | First commit 2026-02-19, latest 2026-04-26 | https://github.com/adhyanthac/h-line-radio-telescope | End-to-end RTL-SDR hydrogen-line (1420.405752 MHz) data collection and analysis workflow with spectrum plotting and a GNU Radio real-time H1 line detector. | Python |
| 3 | EduardoTBuss/nbody-sim | Recently updated (2026) | https://github.com/EduardoTBuss/nbody-sim | Gravitational N-body simulator comparing Euler, semi-implicit Euler, Leapfrog, and RK4 integrators using real NASA JPL Horizons Solar System ephemerides, with energy-conservation validation and Pygame visualization. | Python |
| 4 | KamikazeVildsvin/sonification-celestial-bodies | 2024-04-28 | https://github.com/KamikazeVildsvin/sonification-celestial-bodies | Sonification scripts converting ESA Swarm satellite space-weather data into audio files, used as the compositional foundation for the multidisciplinary art project "Celestial Bodies." | Jupyter Notebook |
| 5 | AriTheGuitarMan/celestial-sonification- | 2025-06-01 | https://github.com/AriTheGuitarMan/celestial-sonification- | Small early-stage app for sonifying celestial/astronomical data into sound (minimal documentation). | HTML |

**Excluded as self-referential:** `omgyjyaswitch7/ephemeris` (this digest's own repository).

---

## Semantic Scholar

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | Evaluation and insights from a sonification-based planetarium show intended for improving inclusivity | 2024-01-08 | https://arxiv.org/abs/2401.04188 | Evaluates "Audio Universe: Tour of the Solar System," an audio-visual planetarium production co-developed with the blind and vision-impaired community; ~90% of 291 audience evaluations rated the sonification components useful and enjoyable. | — |
| 2 | Astroaccesible: A multi-messenger outreach for a multi-messenger science | 2024-09-09 | https://arxiv.org/abs/2409.05505 | Outreach initiative led by a blind astronomer using multi-sensory resources, including sound/sonification, to make astronomy accessible to blind and visually impaired audiences. | — |
| 3 | Harmonices Solaris — Sonification of the Planets | 2023 (ICAD 2023) | https://pdfs.semanticscholar.org/32f6/8208a1cc0db0327c563c28c0ea1f53280a88.pdf | Spatial audio installation sonifying solar-system planets from NASA planetary fact-sheet data via a Markov pitch-set model, using **Open Sound Control (OSC)** within IRCAM's SPAT/XP4Live to drive real-time spatialization across a 6–8 speaker array, with orbital periods scaled into "auditory seconds." | OSC (IRCAM SPAT/XP4Live) |
| 4 | Gravity's Reverb: Listening to Space-Time, or Articulating the Sounds of Gravitational-Wave Detection | 2016 (Cultural Anthropology) | https://www.semanticscholar.org/paper/Gravity%E2%80%99s-Reverb:-Listening-to-Space-Time,-or-the-Helmreich/df27a09a855611c39592a970c5458932c85aeafb | Anthropology-of-science analysis of how LIGO's 2016 gravitational-wave "chirp" detection was rendered audible and rhetorically framed as sound/space data. | — |

**Excluded as off-topic:** "Osc-NetLogo: a Tool for Exploring the Sonification of Complex Systems using NetLogo" (ICMC 2012) — a general-purpose OSC sonification tool for agent-based population models (e.g. predator-prey dynamics) with no astronomy or space-data content; does not meet this digest's astronomy/space scope despite matching the "OSC" keyword.

---

## Notes

- **OSC / Open Sound Control + Astronomy — second match found**: "Harmonices Solaris" (Semantic Scholar item 3) is the second item across all digest runs to directly pair the OSC protocol with astronomy data (after "Stellar Command" in the 2026-06-23 digest), using OSC within IRCAM's SPAT to spatialize sonified planetary data. Still a thin area — two matches total to date — and one additional OSC-tagged candidate (Osc-NetLogo) was excluded this run for having no astronomy content at all.
- **JPL Horizons + Audio**: Still no item pairs Horizons ephemeris data directly with an audio/sonification pipeline. This run's Horizons-related find (`EduardoTBuss/nbody-sim`) extends the growing N-body/Horizons visualization cluster (joining `will-roscoe/nbody`, `w00jay/artemisee`, `stepankaiser/artemis-tracker` from prior digests) but remains visualization-only, not audio output.
- **RTL-SDR Radio Astronomy**: Two new amateur 21 cm hydrogen-line projects this run (`almita-radio/almita`, `adhyanthac/h-line-radio-telescope`), both Python-based RTL-SDR hydrogen-line receivers. Still no project found that combines RTL-SDR output directly with sonification/audio rendering — these remain data-collection/analysis tools, not audio pipelines.
- **Accessibility/outreach sonification — emerging cluster**: This run surfaced an unusually strong cluster of accessibility-focused sonification content: three NASA pages (Episode 160 podcast, "Exploring the Universe Through Sight, Touch, and Sound") and two Semantic Scholar papers (the inclusivity planetarium-show evaluation, Astroaccesible) all center blind/low-vision audiences as the primary use case for astronomical sonification — distinct from the previously catalogued performance/art-installation sonification work (NASA's "Cosmic Cycles" orchestral symphony series, also newly catalogued this run, sits in that latter category instead).
- All entries deduplicated by URL and title against this digest and all 25 prior digests in `Ephemeris/research/` and `research/` (327 previously recorded URLs). All new URLs in this digest were spot-verified for HTTP reachability and content match before inclusion.

---

*Generated by automated research routine · 2026-06-25*
