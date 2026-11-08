# MTG Multiverse

Android-first, browser-based Magic deck-building and goldfish playtest prototype.

## Play on Android
After the GitHub Pages workflow completes, open **https://eighTmile678.github.io/MTG-Multiverse/** in Chrome. Use Chrome's menu → **Add to Home screen** (or Install app) for an app-like launcher icon.

## Features in this recovery build
- Mobile deck builder with automatic local saving
- Scryfall-powered card search (internet required)
- Sample card pack for immediate testing
- JSON import/export and CSV export
- Shuffle, opening hand, simplified mulligan, draw, turn progression, land drops, tapped/untapped battlefield and life counter
- Basic offline shell caching

## Development
This is a static site: open `index.html` in a browser or serve this directory with any static web server. GitHub Actions deploys the repository root to GitHub Pages on pushes to `main`.

## Limitations
This is a prototype, not a comprehensive Magic rules engine. The playtest area is a goldfish sandbox; it does not implement spell legality, priority, the stack, combat, multiplayer, or automated opponent behavior. Scryfall card data is fetched live and is subject to Scryfall's API terms and rate limits. Card data and Magic: The Gathering intellectual property belong to their respective owners. This project is unofficial and not affiliated with Wizards of the Coast.
