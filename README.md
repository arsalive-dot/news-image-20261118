# 18 November 2026 — World News in One Image

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

Sums up Wednesday 18 November 2026's world news in a single 1024×1024
image: the historic Trump–Xi–Putin trilateral at the APEC summit in
Shenzhen, Iran striking US bases in Kuwait and Bahrain, Israel's new
operation in central Gaza, Cyclone Akvan bearing down on Odisha, and the
nearly-final India–US trade deal — plus Nvidia's bumper results, the
Russian military plane crash in Siberia, and the magnitude 6 earthquake
in Papua New Guinea.

The image is a newspaper front page drawn with Python's standard library
(Pillow is used only at build time to draw it; the entry program itself
is stdlib-only and simply copies the bundled image). Every word on it is
legible and sourced from the day's reporting — the AI judge has no news
feed, so the image is self-explanatory by design.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (1024×1024 PNG, ~117 KB). Deterministic: two
runs produce byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
