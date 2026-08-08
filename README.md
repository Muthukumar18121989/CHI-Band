# Continuous Health

An independent product and design concept exploring how a mature health ecosystem
might evolve from **measurement** into **interpretation** — health read against a
person's own baseline rather than a population average.

**Live:** https://chi-band.vercel.app

## Contents

| Path | What it is |
|---|---|
| `index.html` | The concept site — problem, research, vision, ecosystem, platform, intelligence, hardware, app, about |
| `band.html` | The Band — the passive companion, and the power budget that determined its shape |
| `img/` | Product and lifestyle imagery (AI-generated) |
| `teaser/` | Teaser stills, square and wide |
| `og.png` | Social preview card, 2400×1260 |

Both pages are self-contained static HTML — no build step, no dependencies.

## Deploying

Any static host works. On Vercel, import the repo and deploy; the project name
determines the URL.

> **If the deployed URL is not `https://chi-band.vercel.app`**, update the `og:`/`twitter:`
> `content` values and the `<link rel="canonical">` in `index.html` and
> `band.html`. They are absolute by necessity — LinkedIn will not resolve a
> relative `og:image`.

After deploying, run the URL through
[LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/) once to prime
the preview card. LinkedIn caches aggressively on first scrape.

## Research

Every quantitative claim on the site is sourced. Principal sources:

1. Quer G, Gouda P, Galarnyk M, Topol EJ, Steinhubl SR. *Inter- and intraindividual
   variability in daily resting heart rate… cohort study of 92,457 adults.*
   PLOS ONE 15(2): e0227709, 2020. <https://doi.org/10.1371/journal.pone.0227709>
2. Schyvens A-M, Peters B, Van Oost NC, et al. *A performance validation of six
   commercial wrist-worn wearable sleep-tracking devices for sleep stage scoring
   compared to polysomnography.* SLEEP Advances 6(2): zpaf021, 2025.
   <https://doi.org/10.1093/sleepadvances/zpaf021>
3. Apple Inc. *Apple Watch — Battery.* Manufacturer specification.
   <https://www.apple.com/watch/battery/>

No primary user research has been conducted for this concept. The site states this
rather than implying otherwise.

## Disclaimer

An independent product concept by Muthukumar D. **Not affiliated with, authorized
by, or endorsed by Apple Inc.** Apple, Apple Watch, AirPods, iPhone and Apple
Intelligence are trademarks of Apple Inc., referenced for identification only.
Oura, WHOOP and Garmin are trademarks of their respective owners.

Interface mockups are illustrative; figures shown in them are examples, not
measurements. Product imagery is AI-generated and depicts a concept, not a
manufactured device.
