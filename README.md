# Brain Workshop (Web)

Browser port of Brain Workshop 2.0's Dual N-Back. Single HTML file, no build step, phone-friendly.

- 3x3 grid (8 squares, centre unused) + 8 letter sounds (C H K L Q R S T).
- Keys: **A** = position matches N back, **L** = sound matches N back (on-screen buttons too). **Esc** stops.
- Trial length follows BW 2.0 defaults: 3.0 s (N≤3), 3.5 s (N 4–6), 4.0 s (N 7–9).
- Session = 20 + N² trials. First N trials are warm-up (not scored).
- Advance at ≥80%. Three sessions in a row <50% drops one level.
- Progress saved in localStorage of the browser you use.

## Run

Open `index.html` in a browser (Chrome, Edge, Safari, Firefox). Sounds load from `sounds/`, so serve the folder or open the file directly.

## Credits

Letter sounds are from Brain Workshop (GPL-2.0-or-later, Paul Hoskinson, Samantha McVey and contributors, https://github.com/brain-workshop/brainworkshop). Game defaults ported from Brain Workshop 2.0.
