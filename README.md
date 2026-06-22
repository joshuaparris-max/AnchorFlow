# ⚓ AnchorFlow — Calm Focus Flow

A quiet, single-page app for moving from overwhelm to one finished focus block. Built for
ADHD-style "too much at once" moments: pick **one thing**, ground your body, work a short
timer, and close well.

No accounts, no cloud, no notifications — everything stays in your browser.

## The flow

1. **Anchor** — "What is the one thing?"
2. **Ground** — breathe with the circle; tick off body cues (breath, feet, jaw, shoulders, next action).
3. **Focus** — a 5 / 10 / 20-minute timer.
4. **Close** — mark *Done / Still going / Blocked* and add one sentence.

Sessions are saved to **localStorage** and shown in a recent-history list.

## Run

It's one static file:

```bash
# just open it
start index.html        # Windows
# or serve the folder
python -m http.server 8000
```

## Status

See [STATUS.md](STATUS.md). **Working MVP** — full four-step flow with breathing animation,
timer, and saved history.

## Screenshots

_Add screenshots to `docs/` and link them here (e.g. `docs/flow.png`)._

## Privacy

All data is local to your browser. Nothing is transmitted. Clearing site data erases history.
