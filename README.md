# consistency

One habit. One button. One heatmap. Nothing else.

- **Mark today:** tap the circle, or press `Space` / `Enter`. Tap again to undo.
- **Forgot yesterday?** Tap that square in the heatmap to toggle it.
- **Rename it:** click the title.
- **Heatmap shade = chain length** on that day (1–2, 3–6, 7–20, 21+ days), so the longer you go, the brighter it gets.
- Streak doesn't break until a full day is missed — today stays "pending" until midnight.

No account, no server, no build step. Data lives in your browser's `localStorage`;
`export` / `import` gives you a plain JSON backup (`{"days": ["2026-10-03", ...]}`).

## Run it

Open `index.html`, or host it anywhere static. Easiest:

1. GitHub → repo **Settings → Pages** → Source: *Deploy from a branch* → pick the branch, `/ (root)`.
2. Open the URL on your phone → **Add to Home Screen**. It works offline and opens like an app.

Tip: data is per browser/device, so pick one place (your phone's home screen) as the source of truth.
