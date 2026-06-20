# EPHEMERIS DIGEST — 2026-06-20

> Automated research digest covering sonification, radio astronomy, and space data projects.
> Sources: arXiv · NASA · GitHub · Semantic Scholar

---

## arXiv

| # | Title | Date | URL | Summary | Language |
|---|-------|------|-----|---------|----------|
| 1 | Unseen Astronomy | 2026-04-10; *Astronomy & Geophysics* Vol. 67, Issue 2 (Apr 2026) | https://arxiv.org/abs/2604.09250 | Report from a UK National Astronomy Meeting session on multimodal astronomy, surveying community efforts to move beyond purely visual data display — including sonification — in research, education, and outreach. | — |
| 2 | Exploring blazars through sonification. Visual and auditory insights into multifrequency variability | 2025-02-04 (rev. 2026-03-04) | https://arxiv.org/abs/2502.01929 | Applies MIDI Parameter Mapping Sonification to multifrequency light curves of nine blazars, revealing variability patterns across optical, X-ray, and gamma-ray regimes. | — (MIDI/PMSon methodology) |
| 3 | STRAUSS: Sonification Tools & Resources for Analysis Using Sound Synthesis | 2025-04-02 | https://arxiv.org/abs/2504.01660 | Introduces an open-source, flexible sonification package with preset configurations for astronomy, climate science, and other data domains. | Python |
| 4 | herakoi: a sonification experiment for astronomical data | 2024-12-12 | https://arxiv.org/abs/2412.09152 | Open-source tool translating astronomical images into real-time sound via webcam hand-gesture tracking, for accessibility and outreach. | — (webcam hand-tracking + ML) |
| 5 | Toward an auditory Virtual Observatory | 2024-05-18; *J. Audio Eng. Soc.* 72(5), 341–351 | https://arxiv.org/abs/2405.11382 | Prototypes "musification" of stellar spectral library data and Kepler light curves using ML/deep-learning mappings, evaluated by both astronomers and musicians. | — (ML/deep learning) |
| 6 | Sound training platform applied to astronomy | 2024-05-09 | https://arxiv.org/abs/2405.06042 | Describes early development of a platform to teach researchers astronomical data sonification techniques for inclusive multisensory analysis. | — |
| 7 | Multimodal photometry and spectroscopy: a new approach to data analysis in Astrophysics | 2024-04-26; RASTI | https://arxiv.org/abs/2404.17720 | Presents sonoUno applied to spectroscopy/photometry data, designed with direct input from visually impaired end users. | sonoUno (Python) |
| 8 | Analysis of astronomical data through sonification: reaching more inclusion for visual disable scientists | 2024-02-01 | https://arxiv.org/abs/2402.00611 | Describes the sonoUno software and an accessibility framework built around visually impaired researchers' needs. | sonoUno (Python) |
| 9 | Astronomical images sonification: inclusion or outreach? | 2024-02-01 | https://arxiv.org/abs/2402.00952 | Examines whether current sonification tools primarily serve outreach or can enable functionally diverse people to participate as active researchers. | — |
| 10 | Evaluation of the effectiveness of sonification for time series data exploration | 2024-02-15 | https://arxiv.org/abs/2402.09953 | Measures astronomer and non-astronomer performance detecting transit-like signals via visual, auditory, and combined data representations. | — |
| 11 | A Universe of Sound: Processing NASA Data into Sonifications to Explore Participant Response | 2024-03-26; *Frontiers in Communication* | https://arxiv.org/abs/2403.18082 | Sonifies NASA multi-telescope data for three astronomical objects and surveys ~3,184 sighted and blind/low-vision participants on learning, enjoyment, and trust. | — |
| 12 | Galactic Neutral Hydrogen Structures Spectroscopy and Kinematics: Designing a Home Radio Telescope for 21 cm Emission | 2024-10-29 | https://arxiv.org/abs/2411.00057 | Describes an affordable amateur radio telescope (1m dish + H1-LNA + SDR + Raspberry Pi) detecting the 21cm hydrogen line and mapping Milky Way kinematics via Doppler analysis — closest verifiable match to "RTL-SDR radio astronomy" found this run. | SDR + Raspberry Pi (no sonification component) |

---

## NASA

| # | Title | Date | URL | Summary |
|---|-------|------|-----|---------|
| 1 | Listen to This Month's 'Planetary Parade' With NASA's Chandra | 2026-02-25/26 | https://www.nasa.gov/missions/chandra/listen-to-this-months-planetary-parade-with-nasas-chandra/ | Chandra released three new sonifications — Jupiter (X-ray + Hubble infrared, woodwinds), Saturn (X-ray + Cassini optical, synthesizer tones for the rings), and Uranus (X-ray + Keck optical, cello) — timed to February's six-planet alignment, produced by Kimberly Arcand with SYSTEM Sounds. |
| 2 | Radio JOVE Project (recent activity & hardware update) | Ongoing; notable activity 2025-05-13 | https://radiojove.gsfc.nasa.gov/ | NASA citizen-science project where amateurs use SDR receivers (SDRPlay RSP1B/RX-888 MK II) and Radio-Sky Spectrograph software to observe natural radio emissions from Jupiter, the Sun, and the galaxy; new training modules built with the SunRISE Ground Radio Lab. |
| 3 | NASA Data Sonifications Hub | Ongoing (updated 2025-06-10) | https://www.nasa.gov/data-sonifications/ | Central index of NASA's sonification catalog by telescope (Webb, Hubble, Chandra), translating brightness/position into pitch and volume. |
| 4 | A Universe of Sound (Chandra/Smithsonian) | Ongoing (since 2020) | https://chandra.si.edu/sound/ | Flagship NASA/Chandra sonification initiative converting X-ray and multi-wavelength images into sound, including a "Sonification Symphony" with composer Sophie Kastner. |
| 5 | xSonify | Ongoing | http://www.ascl.net/1207.008 | NASA Space Physics Data Facility tool mapping space physics data to audio for visually-impaired researchers and students. |
| 6 | SPDF Audification (CDAWeb) | Ongoing | https://spdf.gsfc.nasa.gov/audification_readme.html | Maps high-resolution heliophysics data (MMS, THEMIS/ARTEMIS, Van Allen Probes, ACE, Wind) directly to audio samples for spectral pattern detection. |
| 7 | HARP — Heliophysics Audified: Resonances in Plasmas | Ongoing (2024 feature) | https://listen.spacescience.org/aboutHARP.html | Sonifies spacecraft magnetosphere measurements, treating the magnetosphere as an "orchestra," with composer Robert Alexander. |
| 8 | NASA Earthdata: "From Data to Melody" | 2023-12-07 (refreshed 2026-03-06) | https://www.earthdata.nasa.gov/news/blog/from-data-melody-data-sonification-its-role-open-science | Discusses sonifying Earth science data (Landsat/Sentinel-2 NDVI, temperature trends) mapped to MIDI chord parameters for open-science accessibility. |

---

## GitHub

| # | Repository | Updated | URL | Summary | Language |
|---|-----------|---------|-----|---------|----------|
| 1 | AuditoryVO/Hands_on_astronomical_data_sonification | 2026-06-18 | https://github.com/AuditoryVO/Hands_on_astronomical_data_sonification | Hands-on materials for an ESMUC "Sonification Workshop" (June 2026) teaching how to convert astronomical/astrophysical data into sound. | Jupyter Notebook, Csound |
| 2 | AuditoryVO/ICAD2026_Workshop (SoniAladin) | 2026-06-13 | https://github.com/AuditoryVO/ICAD2026_Workshop | "SoniAladin" explores the Aladin Sky Atlas through sound, built for an ICAD 2026 workshop under Spain's Virtual Observatory open-science initiative. | Python |
| 3 | ragb/accessdr | 2026-05-25 (v0.6.0) | https://github.com/ragb/accessdr | Accessible SDR application for blind/visually-impaired users — screen-reader-driven, keyboard-operated, with spectrum sonification. | Python |
| 4 | sgoudelis/ground-station | 2026-06-17 (v0.6.0) | https://github.com/sgoudelis/ground-station | Open-source satellite tracking and radio ground-station suite supporting RTL-SDR, SoapySDR, UHD/USRP, and SigMF playback. | JavaScript, Python |
| 5 | nikitodos/seti_klt | ~2026-06-17 | https://github.com/nikitodos/seti_klt | BSc thesis project applying the Karhunen–Loève Transform for RFI cleaning in SETI radio data (Breakthrough Listen), validated with synthetic technosignature injection on SRT/GBT filterbanks. | Python |
| 6 | mef51/frbgui | ~2026-06-17 (release v0.12.0) | https://github.com/mef51/frbgui | GUI for measuring spectro-temporal properties of Fast Radio Bursts from dynamic-spectrum waterfalls via 2D autocorrelation. | Python |
| 7 | JOnathanST29/artemis2-live | Recent (new repo) | https://github.com/JOnathanST29/artemis2-live | Real-time visualization of NASA's Artemis II crewed lunar flyby trajectory powered by live JPL Horizons ephemeris data. | JavaScript, HTML |
| 8 | TrevTron/rtl-ml | Recent/active | https://github.com/TrevTron/rtl-ml | AI-powered radio signal classifier using RTL-SDR + ARM SBC, identifying FM, NOAA Weather, APRS, FRS/GMRS, ISM, and pager signals at 96.9% accuracy. | Python |
| 9 | saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool | 2026-04-16 | https://github.com/saimgulay/Baryon-An-Audio-Visual-Galaxy-Inspection-Sonification-Tool | Interactive galaxy-field viewer and sonification instrument for SDSS DR8 / MPA-JHU catalog data, with supervised sound-mapping and HCI evaluation. | HTML, Python |
| 10 | arda-guler/SOHONIC | 2024-11-23 (older, included for unique topic) | https://github.com/arda-guler/SOHONIC | Sonification of SOHO (Solar and Heliospheric Observatory) satellite data — the only repo found sonifying solar-observatory data. | HTML, CSS |

---

## Semantic Scholar

| # | Title | URL | Summary | Language/Tool |
|---|-------|-----|---------|---------------|
| 1 | Sound-Driven Design in Astronomy | https://www.semanticscholar.org/paper/6f708b87f4cbf29c87d198b85ed41b4f3d2248ac | Recent (late 2025) work on a sound-driven design methodology for astronomy sonification. | — |
| 2 | Evaluating Sonification Effectiveness in Science Education (Edukoi study) | https://www.semanticscholar.org/paper/ddadacbe695f427f076084b9a0e1377f8b1e9300 | Tests the Edukoi sonification tool with 150 middle-school students for color/shape recognition via sound. | Edukoi (built on Herakoi) |
| 3 | Connecting Sound to Data: Workshop Methods | https://www.semanticscholar.org/paper/83d0bcbf6fe2a40514bd2a2841bbaa2355d5bc23 | Participatory workshop methodology for mapping data to sound, with cross-domain applicability including astronomy. | — |
| 4 | CosMonic Sonification Project | https://www.semanticscholar.org/paper/810ac586b16ef73d1c3bfe8cd188a0dc9ea62bc8 | Combines sound-based data analysis with artistic and educational outreach for diverse, inclusive audiences. | — |
| 5 | Micropolyphony and Stochastic Techniques for Sonifying Magnetic Storms | https://www.semanticscholar.org/paper/c3bb20a49ae055ade81f4ba2ef582ee3b9faae76 | Uses stochastic/compositional music techniques to sonify geomagnetic storm data. | — (compositional/musical techniques) |
| 6 | Letting Pulsars Sing: Sonification With Granular Synthesis | https://www.semanticscholar.org/paper/4431ad78ae4f5e3e2058fdbf2554ed9df1053407 | Maps pulsar electromagnetic radiation properties to granular synthesis parameters for auditory representation. | Granular synthesis |
| 7 | Corot Light Curve Ambisonics/Binaural Sonification | https://www.semanticscholar.org/paper/1a733874ac0313cd3c9cbc0d6fb63d70539be1bd | Interactive spatialized (ambisonics/binaural) sonification of CoRoT mission stellar light curves based on astronomical coordinates. | Ambisonics/binaural audio |
| 8 | Data Sonification to Enhance Discovery | https://www.semanticscholar.org/paper/bcf676d48b24b92aa305423c580122441a4b4432 | Demonstrates sonification's role in enhancing discovery in large astronomical datasets and accessibility for BVI researchers. | — |
| 9 | SonoUno development: a User-Centered Sonification software for data analysis | https://www.semanticscholar.org/paper/SonoUno-development:-a-User-Centered-Sonification-Casado-Vega/4fd59dc05fa23926f2de123fce531d21e028710b | Describes the engineering of sonoUno as a modular, ISO 9241-171:2008-compliant sonification tool for 1D/2D/3D data (JOSS, 2024). | Python |
| 10 | Interactive Multimodal Integral Field Spectroscopy (ViewCube) | https://arxiv.org/abs/2412.00185 | Introduces ViewCube, combining interactive visualization with deep-learning binaural sonification for galaxy IFS datacube analysis (CALIFA survey, 67-participant study). | Deep learning (binaural synthesis) |

---

## Notes

- **OSC / Open Sound Control + Astronomy**: No dedicated arXiv, Semantic Scholar, NASA, or GitHub item specifically combining the OSC protocol with astronomy was found this run. Confirms the gap noted in prior digests.
- **JPL Horizons + Audio**: No sonification project paired with JPL Horizons ephemeris data was found. The closest match is `JOnathanST29/artemis2-live` (GitHub) — a real-time *visual* tracker using live Horizons data, not audio.
- **RTL-SDR Radio Astronomy**: Strong GitHub activity this run (`ragb/accessdr`, `sgoudelis/ground-station`, `TrevTron/rtl-ml`, `nikitodos/seti_klt`) and one arXiv hardware paper (2411.00057) on amateur SDR radio telescopes, though none combine RTL-SDR directly with sonification output.
- **Cross-source duplicates**: STRAUSS (arXiv:2504.01660), "Astronomical images sonification: inclusion or outreach?" (arXiv:2402.00952), "Sound training platform applied to astronomy" (arXiv:2405.06042), the sonoUno photometry/spectroscopy paper (arXiv:2404.17720), and the time-series sonification evaluation (arXiv:2402.09953) all also surfaced via Semantic Scholar search; recorded once under arXiv (their primary/original source) per deduplication rule.
- **Excluded as off-topic**: Two Semantic Scholar results outside astronomy/space (a GPCR molecular-dynamics sonification framework and a biological-research sonification survey) were excluded despite matching "sonification" keyword searches.
- All entries deduplicated by URL and title.

---

*Generated by automated research routine · 2026-06-20*
