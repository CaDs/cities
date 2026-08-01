# Cities

Five cities you can walk around in a browser, built from real geospatial data — and why I keep making them.

## Why

I have always been interested in simulating worlds. Whether it's a fantasy tabletop RPG or a 3D simulation, I find it fascinating to think through how a world, a society, an ecosystem would actually work under its own rules.

Lately, one of my favourite ways to test what a new frontier model can do is to hand it exactly that: build me a world. Not a toy scene — a real place, with real terrain and real buildings, and people in it who have somewhere to be.

It started with my home town. I took geospatial data for San Lorenzo de El Escorial and asked Claude to put it back the way it stood around 1570, then wrapped a medieval RPG quest system around the Monastery. Real elevation, real footprints, imaginary century.

Those learnings went straight into the next one: Edo, the shogun's capital, built on the same ground modern Tokyo sits on. And while I was there, I got curious how far the modern city would go — so Tokyo became its own build, at night, at real heights, with real Japanese addresses.

Then I wondered how Codex would handle the same brief, and asked it for Panama City. It did — in a noticeably different flavour. And when Ornith arrived I gave it the hardest of the Japanese briefs: Kyoto, where the ground is a basin instead of a plain and the city is temples rather than a castle town.

> These are not perfect representations. They're full of inconsistencies and bugs. What I find interesting is watching these models take real data and spin a society out of it — small worlds, simulated well enough to walk through.

## The cities

| City | Built with | Walk it | Source |
|---|---|---|---|
| **San Lorenzo, 1570** — my home town as it stood around 1570, with a medieval quest system around the Monastery of San Lorenzo de El Escorial. Where all of this started. | Claude | [open](https://cads.github.io/san-lorenzo-1570/web/) | [repo](https://github.com/CaDs/san-lorenzo-1570) |
| **Edo** — the same ground Tokyo sits on, rolled back to the shogun's capital. Real GSI terrain and OSM footprints, dressed as Edo. | Claude | [open](https://cads.github.io/edo/web/) | [repo](https://github.com/CaDs/edo) |
| **Tokyo** — how much of the modern city can you actually simulate? Greater Tokyo after dark, real elevation, real buildings at real heights, live Japanese addresses. | Claude | [open](https://cads.github.io/tokyo/web/) | [repo](https://github.com/CaDs/tokyo) |
| **Panama City** — the same brief, handed to a different model. A playable modern Panama City with NPCs and quests. | Codex | [open](https://cads.github.io/panama/web/) | [repo](https://github.com/CaDs/panama) |
| **Kyoto** — the imperial capital in the Edo period. The Kamo River corridor climbing into the Higashiyama hills, Nijo Castle on its real moats, errands built from the place names that survived the century. | Ornith | [open](https://cads.github.io/kyoto/web/) | [repo](https://github.com/CaDs/kyoto) |

## What this is not

This is not a benchmark. One build per model, my prompting drifts between runs, and each of these is as much a record of my nudging as of any model's ability. Which is exactly why they're public — go walk around in them and judge for yourself.

---

By [Carlos Donderis](https://github.com/CaDs). This repo is just the index page (`index.html`); each city lives in its own repo above.
