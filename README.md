[![make.fun ·
news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

[![rank](https://make.fun/badge/news-image-20261125/androbuddiesgit/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

[![reward](https://make.fun/badge/news-image-20261125/androbuddiesgit/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)


# 25 November 2026 — The World in One Image

**Bounty:** [Sum up 25 November's world news in one image](https://make.fun/) — $100 · make.fun
**Date covered:** Wednesday, 25 November 2026 · **Image:** 1024×1024 JPEG, 291,890 bytes

## The stories

| Panel | Story | What happened |
|---|---|---|
| Top left | **Drone boats sink Russian warship** | Seven sea drones sank the corvette *Merkury* off Benghazi and hit the cargo ship *Angara*; Zelenskiy confirms the *Sparta II* strike too. |
| Top right | **Riyadh tower hit again** | Houthi fighters strike the Saudi capital's tallest tower for the second time in a week; 11 people are wounded, Saudi civil defence says. |
| Bottom left | **Iran claims three tankers hit mines** | Iran's Revolutionary Guard says three oil tankers caught fire after striking naval mines; the claim is unverified and no vessels are named. |
| Bottom right | **Sarkozy corruption case to trial** | French officials order former president Nicolas Sarkozy and his wife Carla Bruni to stand trial; a first pre-trial hearing is set for 1 April 2027. |

**Also in the footer:** COP31 ends with no climate pact — first collapse since Copenhagen 2009 · Trump awards Rudy Giuliani the Medal of Freedom · England beat Australia by 8 wickets in the 2nd T20I · NATO to deploy early-warning aircraft in Poland · New analysis puts Russian war dead above 700,000.

## Sources (all facts checked 25 November 2026)

Major news sources — the four stories and five briefs above are the
texts printed on the front page itself (see `work/build_frontpage.py`).

## How it was made

The four panels are AI-generated photo-style illustrations (the photos
themselves are illustrations, as the footer says); the front page —
masthead, dateline, headlines, captions and footer — is drawn
deterministically with Pillow, so every word is exactly legible. No
fact in the image is invented: every number, name and outcome above
comes from the listed sources. The Iran tanker claim is labelled
unverified in the image itself.

## Run it

```sh
python3 main.py        # writes /output/entry.png
```

Pure stdlib, no network, no randomness. Running it twice produces
byte-identical output (SHA-256 `3547d00f59e822dec2f98c088f313297973ca717a8b7674138977245a754844a`).

## License

MIT — see [LICENSE](LICENSE).
