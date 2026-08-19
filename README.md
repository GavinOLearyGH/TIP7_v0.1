# TIP7 v0.1

A deliberately simple, phone-first prototype of a **3 Day / 7 Minute Mobility Challenge for golfers**.

## Prototype goal

Test whether the 7 Minute Workout Challenge interaction model translates well to golf mobility:

- press Start and stop making decisions
- one exercise at a time
- 30 seconds of movement
- 10 second automatic changeover
- sound/vibration cues
- concise instruction plus a simple “feel” cue
- progress through 12 movements
- completion tracking and a tiny TIP check-in

## Days

1. **MOVE** — Find your range
2. **OPEN** — Create more space
3. **ROTATE** — Move like a golfer

## Running it

`index.html` has no dependencies or build step. Open it directly in a browser, or publish the `main` branch with GitHub Pages using the repository root as the Pages source.

The prototype stores day completion, selected day, sound preference and the post-session `Tighter / Same / Looser` check-in in browser `localStorage`.

## Timing

Each day uses 12 × 30-second movement intervals and 11 × 10-second changeovers, for a total guided sequence of **7:50**. This intentionally mirrors the simplicity of the 7-minute workout pattern rather than forcing the clock to exactly 7:00.

## Safety

The prototype tells users to move only through a comfortable, pain-free range. It is intended as general mobility guidance, not medical or rehabilitation advice.
