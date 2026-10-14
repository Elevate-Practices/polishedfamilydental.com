# polishedfamilydental.com

Static site for Polished Family Dental (Fort Worth and Glen Rose, TX), built from
`Elevate-Practices/elevate-agents/sites/polished/` with `python3 build.py site`. Don't edit files here by hand; edit the build and republish.

- Preview: https://polished.elevatepractices.com (robots blocked, `noindex`) until launch.
- Launch: set `LAUNCH = True` in build.py, rebuild, copy `out/site/` here (CNAME becomes polishedfamilydental.com), then point DNS.
- `/book-fort-worth/` and `/book-glen-rose/` forward to each office's Modento booking page.
