# Training Notes

## Current Weekly Structure (3 run + 3 strength, strength-first)

- Mon: run + light bench (volume/technique)
- Tue: heavy squat
- Wed: run (+ optional strides)
- Thu: heavy bench + light/medium squat (or leg extension if fatigue/DOMS)
- Fri: run (easy LSD)
- Sat: deadlift day (+ optional medium bench if recovered)
- Sun: full rest

## Execution Rules

- Same-day run + strength: prioritize strength first, or split sessions.
- Main lift rest: 3-5 min.
- Prioritize movement quality; do not grind into failure.
- Main lifts: log `rir_last` first; accessories can log `rpe_last`.

## Progression Rules

- Increase load only when target work remains at least 1 RIR or movement is very stable.
- If form breaks (bar path drift, depth unstable, back loose, obvious grind), switch to Plan B immediately.
- New-load progression:
  - `load x 5 x 1 + old_load x 5 x 2`
  - `load x 5 x 2`
  - `load x 5 x 3`
  - then move to next increment
- New deadlift loads start with 2 work sets; if set 1 feels off, regress and complete back-off volume.

## Logging Rules

- CSV is the only historical source of truth.
- Logs are append-only whenever possible.
- Week format: `YYYY-Www` (example: `2026-W10`).
