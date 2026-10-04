# Why a Plastic Container Leaks Only Above a Critical Level

Lecture notes on one question. A plastic takeout container holds water below a certain level. Above that level, it leaks 1 drop per second through a small hole. Why?

**Read the notes: https://az9713.github.io/leaky-container-physics/**

## What the notes explain

0. A visual dictionary of the symbols and the container.
1. Why there is a threshold: hydrostatic pressure against capillary pressure.
2. Why the leak is slow: a small hole, viscous loss, and exit kinetic energy.
3. Why the water leaves as discrete drops: Tate's law.
4. Numbers for the container (9.4 x 4.2 x 3.1 in).
5. Glossary.

## Main results

| Quantity | Value |
|---|---|
| Surface tension, water | 0.072 N/m |
| Contact angle (assumed) | 110 deg |
| Maximum capillary hold-up height, H_max | 7.874 cm |
| Drop volume, V_drop | 27.7 uL |
| Fitted hole radius for 1 drop/s | 0.1256 mm |
| Critical level, H_crit, at r = 0.08 / 0.10 / 0.12 / 0.15 mm | 6.24 / 4.99 / 4.16 / 3.33 cm |
| Leak at r = 0.12 mm (2006 mL start) | 946 mL leaks, 1059 mL stays |
| Time to 63.2% of the leak / 99% | 9.98 h / 37.6 h |

## Assumptions

- The rate of 1 drop/s is an estimate, not a timed measurement.
- Contact angle 110 deg, outer hole radius 1 mm, and Harkins-Brown factor f = 0.6 are assumed.
- The container has straight walls (water surface area 254.7 cm^2). A real container usually tapers, so the true area can be smaller. The leak times scale as 1/area.
- Some coefficients are not checked against a source. The notes mark each one.

## Files

- `index.html` - the notes. One self-contained file. The four figures are inline SVG. The equations load MathJax from `cdn.jsdelivr.net`, so the page needs an internet connection.
- `README.md` - this file.

GitHub Pages serves `index.html` from branch `main`, folder `/`.
