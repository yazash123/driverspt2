# Underlying drivers, Part 2 (Sunday)

The House of the People "connecting drivers" Part 2 activity (Sunday 25 Oct): the Driver Threads map, running on its own in place of claude.ai.

- **Live page:** https://yazash123.github.io/driverspt2/
- **In Webflow:** paste `webflow-embed.html` into one Code Embed in a full-width section (not a Container).
- **Source:** the claude.ai artifact "HotP Driver Threads" (https://claude.ai/artifact/S2dr8g2D5rgtY4grxj6y4s).

## Files

| file | what it is |
|---|---|
| `index.html` | the page, exactly as published from the claude.ai artifact "HotP Driver Threads". Don't hand-edit it; re-export from the artifact instead. |
| `webflow-embed.html` | the one Webflow embed. |
| `.nojekyll` | tells GitHub Pages to serve the page as is. |

## How it works

Nothing needs a backend: Saturday's anonymised `drv-s6` links are built into the page (`MAPS`, `OWN`), so it makes no Firebase reads.

- **Set up** asks for the room (1–26). The green bar then shows Explore and the room's drivers (`ROOMDRV`); the Room menu on the right changes room. `…/driverspt2/#g5` opens room 5 directly.
- **What to do** (the white pill) holds the question, the steps and, under More help, the room's risk and drivers.
- The settings button holds Count (Credits by default), Members' drivers and "Driver 7 (gaps in rules)", which is counted by default.

The artifact's "Edit text" bar only appears inside claude.ai, so it stays hidden here. To change copy, edit it in the artifact and replace `index.html`.

## Publishing

Repo Settings → Pages → Deploy from a branch → `main` / root.
