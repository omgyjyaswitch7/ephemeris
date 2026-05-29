# Ephemeris Project — Claude Configuration

## Identity
- GitHub: https://github.com/omgyjyaswitch7
- Email: omer@sarigedik.com

## Daily Digest Routine

Each time the research digest is run:

1. **Generate** the digest to `Ephemeris/research/EPHEMERIS_DIGEST_YYYY-MM-DD.md`
2. **Push to GitHub**: commit and push to https://github.com/omgyjyaswitch7/ephemeris (branch: main)
3. **Email**: create a Gmail draft to omer@sarigedik.com with the digest as formatted HTML

### GitHub Push Commands (after generating digest)
```bash
cd /home/user
git add Ephemeris/research/EPHEMERIS_DIGEST_*.md
git commit -m "digest: YYYY-MM-DD"
git push -u origin main
```

### GitHub Setup (one-time, requires GITHUB_TOKEN env variable)
```bash
curl -H "Authorization: token $GITHUB_TOKEN" \
     -d '{"name":"ephemeris","description":"Daily astronomy research digest","private":false}' \
     https://api.github.com/user/repos

git remote add origin https://omgyjyaswitch7:$GITHUB_TOKEN@github.com/omgyjyaswitch7/ephemeris.git
```

## Research Topics
- sonification astronomy
- radio astronomy sound data
- astronomical data sonification
- JPL Horizons data mapping
- space data audio visualization
- OSC open sound control astronomy
- celestial mechanics audio
- RTL-SDR radio astronomy

## Output Format
- File: `Ephemeris/research/EPHEMERIS_DIGEST_YYYY-MM-DD.md`
- Organized by source: arXiv · NASA/JPL · GitHub · Semantic Scholar
- Each entry: title, URL, date, one-sentence summary
- Deduplicated by URL
- Research gaps noted at the end
