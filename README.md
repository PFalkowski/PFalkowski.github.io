# PFalkowski.github.io

This repository serves `https://pfalkowski.github.io/` and contains **nothing but a redirect**.

## Why

There used to be two CVs.

- This repository held a hand-written HTML CV at the root.
- [`PFalkowski/cv`](https://github.com/PFalkowski/cv) held a second one at `/cv/`.

They shared a design ancestor and then drifted. By August 2026 the copy here was roughly two years
behind: it ended at Seville More Helory, so it was missing StoneX and Happy Team entirely, had no
Jagiellonian University research role, no Other Projects section, and no Polish version. Anyone
who found the root URL read a stale CV, and search engines had two competing versions of the same
document to pick between.

## The one CV

**https://pfalkowski.github.io/cv/** — built from [`PFalkowski/cv`](https://github.com/PFalkowski/cv),
which is where every content edit belongs. Polish version at `/cv/pl/`.

That URL is also the one printed on the PDF CV in circulation, which is why it won rather than the
root.

## This page

`index.html` redirects three ways over — `meta refresh`, `location.replace`, and a visible link if
both are blocked — and carries `rel="canonical"` plus `noindex, follow` so the crawlers consolidate
on `/cv/`.

Do not add content here. If you want to change the CV, change `PFalkowski/cv`.
