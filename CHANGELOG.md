# Changelog

## Original
- The game as received (single index.html).

## Fixes (QA round 2026-11-18)
- Phone landscape: the playfield no longer overflows the screen height (the bottom ~20% was cut off on a 915x412 phone).
- Touch steering: the browser no longer takes over a finger drag (pan / pull-to-refresh), so the ship keeps following the finger.
- Phone held upright: a "turn the phone" hint instead of a tiny strip-sized playfield.
- Laser emitter: shots now hit the emitter where it is drawn (it bobs up and down; the hit point stayed at its start height).
- Boss: flying into the Overlord now costs a shield like any other hit (it could be passed through).
- Boss health bar: starts full again on a new run (it stayed empty after a win).
