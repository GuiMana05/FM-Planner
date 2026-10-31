# FM Planner

A web app for planning and comparing Football Manager squads. Import your squad data, organise your lineup and compare players side by side.

**Live demo:** https://GuiMana05.github.io/FM-Planner/

## Features

- **Squad planning:** organise your players and build your squad around positions.
- **CSV importer:** bring in your squad data from a CSV export. Positions are normalised automatically and players are matched against existing entries, so re-importing doesn't create duplicates.
- **Player comparison:** compare players side by side, including image-based analysis of player data.
- **Persistent data:** everything is saved in your browser with `localStorage`, so your squad is still there when you come back.

## Tech

- Single-file app: plain HTML, CSS and vanilla JavaScript, no build step and no dependencies to install.
- Started as a React prototype with data migrated from Excel, then simplified into one standalone file.
- Client-side only: no backend, no accounts, your data never leaves your browser.

## Run it locally

1. Download `index.html`.
2. Open it in any modern browser.

## Notes

Data is stored per browser. Clearing your site data or switching browsers/devices starts you with an empty squad.

## Author

Built by Guilherme.
