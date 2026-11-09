# QT Cycle + SSMT Tool

Quarter Theory cycle stack, SSMT validity, and HTF→LTF assimilation — browser-only, no build step.

## Open locally

Open `index.html` in any modern browser (Chrome, Safari, Firefox, Edge).

## GitHub Pages

1. Create a new repo
2. Upload `index.html` (and this README)
3. Settings → Pages → Deploy from branch `main` / root
4. Site will be at `https://<user>.github.io/<repo>/`

## Features

- Live **New York** clock with seconds + live sequence code
- Tap Year (1971–2028) / Month / Day; time picker for NY time
- **Use Current NY Time** uses `America/New_York` (not device local)
- Full stack: Quadrennial → nano
- Weekly labels: Q1 Monday · Q2 Tuesday · Q3 Wednesday · Q4 Thursday  
  (windows still anchor Sunday 18:00 NY)
- SSMT validity vs sequence above (including Q4·Q4·Q1·Q2 path)
- Highest 3-consecutive sequence in the full stack
- Neighbour sequence + valid setup quarter (+1 on 2nd digit)
- HTF→LTF allowed mappings

## Weekly quarters (Sunday 18:00 NY anchor)

| Quarter | Window (NY) | Day label |
|---------|-------------|-----------|
| Q1 | Sun 18:00 → Mon 18:00 | Monday |
| Q2 | Mon 18:00 → Tue 18:00 | Tuesday |
| Q3 | Tue 18:00 → Wed 18:00 | Wednesday |
| Q4 | Wed 18:00 → Thu 18:00 | Thursday |
