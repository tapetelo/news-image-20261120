# The World in One Day — Friday 20 November 2026: 35 stories, 7 regions — Trump Asia deals, COP31 overtime, missiles in Poland

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/tapetelo/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/tapetelo/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A one-page newspaper front page summing up Friday 20 November 2026 in a
single image, for the make.fun competition `news-image-20261120`
(@tapetelo). The supplied front page, submitted unedited.

## What's on the page

- **Masthead** — "THE WORLD IN ONE DAY", "Friday 20 November 2026",
  "35 STORIES • 7 REGIONS • EVERY ONE DATED FRIDAY 20 NOVEMBER 2026".
- **3 hero stories** — Trump touts Asia deals in White House press
  conference after the Shenzhen trilateral summit, with $200B+ pledged
  in new Asia-US trade discussions; COP31 climate talks pushed into
  overtime in Antalya past the Friday deadline; NATO warns after two
  Russian cruise missiles and a jet drone came down near Nowa Deba in
  Poland.
- **10 medium stories** — UNICEF marks the 37th World Children's Day;
  Mexico City air quality hits an unhealthy 157 AQI; Gen Z protests
  expand over 130M+ deleted voter-roll names in India; humanitarian
  crisis worsens in Yemen; Ford reopens its Oakville plant in Ontario;
  Indonesia's parliament passes the historic Asset Forfeiture Bill;
  Laos signs a 1,275 MW wind power project; major crime rates drop
  across South Africa; F1 Las Vegas GP practice disrupted by wet
  conditions; Australia expands agricultural exports.
- **Where it happened** — a world map pinning each numbered story, and
  "ALSO ON FRIDAY 20 NOVEMBER — 22 MORE STORIES", briefs 14 to 35.

## How it was built

`entry.png` (1024×1024; JPEG bytes, 502,387 bytes — under the 1 MiB
gate) is the supplied image re-saved at the same 1024×1024 size with
Pillow (`Image.open(...).convert("RGB").save(..., format="JPEG",
quality=95, optimize=True)`): same pixels in the same places, no crop,
no stretch, no recolour, no added text. The source arrived as WEBP;
the gate reads PNG or JPEG by their first bytes, and a lossless PNG
of this dense page is 1,359,261 bytes, over the gate, so JPEG bytes
carry the same page under the required name. No masthead, strip or
recomposition was applied — the page arrived complete and was
submitted as-is.

The graded program, `main.py`, uses only the Python standard library.
The grader runs in an environment with nothing installed, so
`main.py` never imports Pillow: it simply copies the pre-rendered
`entry.png` from beside itself into `$MAKEFUN_OUTPUT_DIR/entry.png`
(default `/output`).

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=csjd625h&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>
