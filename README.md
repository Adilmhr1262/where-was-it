# WhereWasIt

A personal item-location tracker. Record where you put things, search instantly, move items in one step, and keep a location history. One person, one browser, no account, no server.

## Pages

- Home: instant search, favorites, recently updated items
- All Items: browse, search, filter by category and place
- Item Details: photo, notes, one-step move, full location history, edit, delete
- Settings: export/import JSON backup, saved places, clear all data

## Features

- Add items with name, place, category, notes, optional photo (image only, max 5 MB)
- Favorites pinned to Home
- Location history recorded automatically on every move, with date and time
- Saved places reused as suggestions
- IndexedDB persistence: items and photos survive refreshes
- Import validates the whole file before writing anything; duplicates are skipped, never overwritten
- Starts empty. No sample items, no fake data

## Run

Open `index.html` in any modern browser. No build step, no dependencies to install.

## Data

Everything stays in the browser's IndexedDB. Export produces a single JSON file (photos included as image data). Nothing is sent anywhere.
