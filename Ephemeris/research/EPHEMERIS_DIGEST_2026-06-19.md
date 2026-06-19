# EPHEMERIS DIGEST — 2026-06-19

> Automated research collection on radio astronomy, sonification, and space data.
> Sources: arXiv · NASA · GitHub · Semantic Scholar
> Search terms: sonification astronomy · radio astronomy sound data · astronomical data sonification · JPL Horizons data mapping · space data audio visualization · OSC open sound control astronomy · celestial mechanics audio · RTL-SDR radio astronomy

---

## arXiv

| # | Title | Date | URL | Summary | Language / Tools |
|---|-------|------|-----|---------|-----------------|
| 1 | Generative Musical Exploration of Astronomical Catalogs | 2026-04-08 (EvoMUSART 2026 proceedings) | https://link.springer.com/chapter/10.1007/978-3-032-24350-8_6 | Applies BLS periodograms and an LSTM-based generative model to turn light curves from the INTEGRAL/OMC variable-source catalog (via the Spanish Virtual Observatory) into music cross-matched with a Mozart-derived composition. | Python (inferred; LSTM pipeline) |
| 2 | A case study of translating sonifications across musical cultures for an educational application | 2025-06-09 | https://arxiv.org/abs/2506.08096 | Adapts a Western-classical-style sonification show about the Solar System for Caribbean audiences, examining how cultural musical context affects accessibility and comprehension of astronomy sonifications. | — |

No 2026-dated arXiv preprints were found this sweep; both new entries are previously-uncatalogued items newly indexed (a 2026 conference chapter and a 2025 preprint). A direct arXiv API query (sorted by submission date) was rate-limited during this sweep; results above were obtained via targeted searches and cross-checked against the existing digest history.

---

## NASA

| # | Title | Date | URL | Summary | Language / Tools |
|---|-------|------|-----|---------|-----------------|
| 1 | Radio JOVE | Launched 1999; last updated 2026-01-23 | https://science.nasa.gov/citizen-science/radio-jove/ | NASA citizen-science project where participants build $300–500 radio spectrograph kits (16–24 MHz) to detect and record radio emissions from Jupiter, the Sun, and the Milky Way. | Radio-Sky Spectrograph software (language unspecified) |
| 2 | HARP — Heliophysics Audified: Resonances in Plasmas | Ongoing (pilot launched 2023; team/about pages current as of this sweep) | https://listen.spacescience.org/about.php | NASA-funded citizen-science platform that audifies THEMIS spacecraft electromagnetic-wave measurements from Earth's magnetosphere so volunteers can listen for plasma-wave patterns, building on the MUSICS project. | Web-based interface (language unspecified) |

---

## GitHub

| # | Repository | Last Updated | URL | Summary | Language |
|---|-----------|-------------|-----|---------|---------|
| 1 | interactive-sonification/pya | 2023-12-10 (v0.5.2; newly indexed this sweep) | https://github.com/interactive-sonification/pya | General-purpose Python audio/DSP toolkit (numpy-based signal processing, synthesis, auditory display) used as a building block by several astronomy-sonification projects. | Python |
| 2 | cadojo/HorizonsAPI.jl | 2023-04-29 (v0.1.0; archived 2024-06-09; newly indexed this sweep) | https://github.com/cadojo/HorizonsAPI.jl | Julia wrapper around JPL's HORIZONS REST API for retrieving solar-system body position/velocity ephemerides. | Julia |

---

## Semantic Scholar

No previously-uncatalogued papers found this sweep. The Semantic Scholar Graph API returned HTTP 429 (rate-limited, no API key configured) for all four direct queries; targeted web searches for "celestial mechanics" + audio/sonification, RTL-SDR + radio astronomy, and OSC + space data surfaced only items already present in prior digests (CosMonic, herakoi, the blazar-sonification preprint, generic OSC-protocol papers) or non-astronomy matches.

---

## Notes

- **New this sweep vs 2026-06-18**: 2 arXiv items, 2 NASA citizen-science projects, and 2 GitHub repositories — a quiet sweep overall, consistent with recent days.
- **arXiv**: No genuinely new (2026-submitted) preprints were found; the two items above are previously-uncatalogued older items (a April 2026 conference chapter and a June 2025 preprint) surfaced by deeper queries this sweep.
- **NASA**: Both new entries are established, ongoing citizen-science programs (Radio JOVE since 1999, HARP since 2023) not previously catalogued, rather than new 2026 releases. The Chandra "planetary parade" Jupiter/Saturn/Uranus sonifications (Feb 2026) and the official Webb/Hubble sonification hubs were re-checked and remain fully catalogued from prior sweeps.
- **JPL Horizons data mapping**: No new repository combining Horizons ephemeris data with audio/sonification was found; `cadojo/HorizonsAPI.jl` (Julia, archived) is a data-access wrapper only, newly indexed but not audio-related.
- **OSC (Open Sound Control)**: No astronomy-specific OSC project found this sweep; searches for `"celestial mechanics" audio orbit` and `open sound control space data` returned only generic OSC-protocol papers and previously-catalogued projects (e.g. `sesselastronaut/celestialBodyTracking`, `arda-guler/SOHONIC`).
- **RTL-SDR**: No new dedicated RTL-SDR radio-astronomy project found; existing hydrogen-line / amateur radio-telescope writeups (rtl-sdr.com, Sonoma State University) and `evanmayer/rtlobs` remain the most relevant prior catalogue entries. A new general-purpose "Ground Station" SDR satellite-tracking platform was found but excluded as out-of-scope (satellite/weather-imagery decoding, not radio astronomy).
- **Semantic Scholar**: API rate-limited (HTTP 429) for all direct queries this sweep; relied on web search cross-referencing instead, which found no uncatalogued papers.
- **Deduplication**: All candidate results were checked against the full URL/title history extracted from every prior digest in `Ephemeris/research/` and the legacy `research/` directory (249 known URLs); only previously uncatalogued items are listed above.
- All URLs verified at time of collection (2026-06-19).

---

*Generated by Claude Code · Ephemeris Project · 2026-06-19*
