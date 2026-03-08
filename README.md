# WHOO? / WHUT?

A touch-based mobile web app for board game nights. Two tools in one — a player picker and a dice roller.

**Live:** [ctrl-dallinger.github.io/player-picker](https://ctrl-dallinger.github.io/player-picker/)

---

## WHOO? — Game Picker

All players place a finger on the screen and hold. After ~2 seconds, one of three outcomes is revealed:

- **First** — one random player is chosen to go first
- **Order** — all players are shuffled into a ranked play order
- **Teams** — players are randomly split into 2–5 teams

Supports up to 10 simultaneous touches. Each finger gets a unique colour. Results appear as a centred card while finger dots remain visible on screen.

---

## WHUT? — Dice Roller

Mix-and-match dice roller supporting the full standard RPG dice set:

**D4 · D6 · D8 · D10 · D12 · D20 · D100**

- Tap a die type to activate it and focus the quantity selector
- Tap again to switch focus between active dice, or deactivate
- Set 1–10 of each die type independently
- Roll any combination simultaneously
- Results grouped by die type, sorted highest to lowest within each group
- Per-group subtotals and grand total displayed

---

## Tech

Single HTML file. No frameworks, no dependencies beyond Google Fonts. Works on mobile and desktop.
