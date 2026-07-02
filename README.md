# RUN, ZARNA, RUN!

A bright 16-bit NYC side-scroller: Zarna Garg sprints across the city, bonking
angry aunties, divebombing pigeons, pizza rats, and judgy uncles with frying
pans to rescue her family from her mother-in-law.

**Play it:** enable GitHub Pages (Settings → Pages → Deploy from branch →
`main` → `/ (root)`) and open the published URL on your phone.

- One file, zero dependencies: `index.html` (HTML5 canvas + WebAudio, all art
  and music generated in code).
- **Your own title / ending art:** commit images to the **repo root** —
  `intro2.png` (used full-screen as the title background, with the RUN, ZARNA,
  RUN! marquee and menu text drawn on top) and, optionally, `family.png` (shown
  full-screen after the rescue, before the score). The game auto-detects them on
  load and falls back to drawn scenes if absent. They load with a `?v=1`
  cache-buster; if you replace one later, bump the version in `index.html`.
- Mobile: drag on the left half to move, JUMP / PAN buttons on the right
  (tapping the right half also jumps).
- Desktop: arrows / AD to move, Space to jump, X or F to throw pans.
- Collect pineapples (10 = extra heart), drink chai, grab the mic for Comedy
  Special mode, and save the family.
