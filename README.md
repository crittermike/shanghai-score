# Shanghai Score

A mobile-first web app for keeping score in the card game **Shanghai** (a Contract Rummy variant with 10 rounds).

## Rounds / Contracts

1. 2 Sets of 3
2. 1 Set of 3 + 1 Run of 4
3. 2 Runs of 4
4. 3 Sets of 3
5. 1 Set of 3 + 1 Run of 7
6. 2 Sets of 3 + 1 Run of 5
7. 3 Runs of 4
8. 1 Set of 3 + 1 Run of 10
9. 3 Sets of 3 + 1 Run of 5
10. 3 Runs of 5

## Features

- 2–8 players with editable names
- Per-round score entry (points left in hand; lowest total wins)
- Running totals with a leader crown
- Undo last round, start new game (keeps names)
- All data saved to `localStorage` — no accounts, no server
- Built for phone screens

## Use

Open the [live app](https://crittermike.github.io/shanghai-score/). Works offline once loaded.

Single static `index.html`, no build step.
