# Underlying drivers, Part 2 (Sunday)

The House of the People "Underlying drivers, Part 2" activity, running on its own in place of claude.ai.

- **Live page:** https://yazash123.github.io/driverspt2/
- **In Webflow:** paste `webflow-embed.html` into one Code Embed in a full-width section (not a Container). Part 2 has no room links: every room sees the same page.

## Files

| file | what it is |
|---|---|
| `index.html` | the page, exactly as published from the claude.ai artifact. Don't hand-edit it; re-export from the artifact instead. |
| `webflow-embed.html` | the one Webflow embed. |
| `.nojekyll` | tells GitHub Pages to serve the page as is. |

## How it works

Nothing needs a backend. Part 2 is a read-only presentation: Saturday's results are built into the page (`P2EX`), so it makes no Firebase reads and can't break mid-session. It shows example numbers until Saturday's `drv-s6` export is worked out and written in. The drivers are Jacob's seven, numbered D1 to D7 as in Part 1.

The artifact's "Edit text" bar only appears inside claude.ai, so it stays hidden here. To change copy, edit it in the artifact and replace `index.html`.

## Publishing

Repo Settings → Pages → Deploy from a branch → `main` / root.
