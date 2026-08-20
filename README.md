# TIP7 v0.2

A deliberately simple, phone-first prototype of **TIP7: seven minutes a day of Stretch + Strength for golfers**.

## Prototype goal

Test the habit loop:

**Open it → complete today's circuit → leave → come back tomorrow.**

TIP7 sits alongside TIP Plans and Sessions. It is not another coaching plan. It is the small daily physical habit layer for TIP's **Stretch** and **Strength** dimensions.

## Level 1 — FOUNDATION

Seven calendar days:

1. **STRETCH — OPEN** — Create some space.
2. **STRENGTH — STABLE** — Build the foundation.
3. **STRETCH — ROTATE** — Turn without forcing it.
4. **STRENGTH — BASE** — Build from the ground up.
5. **STRETCH — RESTORE** — Move everything.
6. **STRENGTH — CONTROL** — Own your movement.
7. **STRETCH + STRENGTH — COMPLETE** — Put the week together.

Each circuit uses **12 × 30-second work intervals** with **10-second automatic changeovers**. Sound and vibration cues move the golfer through the circuit without needing to touch the phone.

## Challenge architecture

Level 1 is the first row of the eventual **7 Levels × 7 Days = 49 Day TIP7 Challenge**.

The design intent is progressive: Level 1 establishes the movement vocabulary and daily habit. Later levels can progressively increase range, stability, strength, rotational demand and performance intent while preserving the same simple interaction model.

## Streak behavior

The prototype tracks:

- current streak
- best streak
- lifetime TIP7 completions
- Level 1 day completion
- simple post-circuit check-ins

A completed circuit unlocks the next challenge day on the **next calendar day**. Missing a calendar day breaks the current streak, but completed work is never erased.

A small **Reset prototype progress** control remains in v0.2 for testing.

## Running it

`index.html` has no dependencies and no build step. Open it directly in a browser, or publish the `main` branch with GitHub Pages using the repository root as the Pages source.

All prototype progress is stored locally in browser `localStorage`.

## Timing

The guided sequence is approximately **7:50**: 12 × 30 seconds of work plus 11 × 10-second changeovers. This preserves the circuit pattern rather than artificially shortening the exercise intervals to make elapsed time exactly 7:00.

## Safety

TIP7 asks users to work through a comfortable, pain-free range and stop movements that cause pain. It is intended as general fitness programming, not medical or rehabilitation advice.
