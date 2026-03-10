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

## Deadlift Setup Notes

- Preload must not become bar break from floor.
- Deadlift setup order:
  - midfoot pressure
  - brace
  - lats locked
  - pull slack out of the bar
  - pause briefly while the bar is still on the floor
  - then push the floor away
- Self-check:
  - if the body gets tight but the bar stays down, setup is correct
  - if the bar leaves the floor during preload, setup overshot and needs a reset
- Main cue: `pull slack, do not lift yet; then push the floor`

## Logging Rules

- CSV is the only historical source of truth.
- Logs are append-only whenever possible.
- Week format: `YYYY-Www` (example: `2026-W10`).
- Planned sessions should also be recorded in `plan_log.csv` so plan vs. completion can be reviewed later.
- Suggested `plan_log.csv` usage:
  - `planned_main`: main lift or main session prescription
  - `plan_b`: fallback if Plan A is not completed cleanly
  - `planned_accessories`: accessory checklist
  - `planned_run`: run prescription if included that day
  - `completed_*`: what was actually done
  - `status`: `planned`, `completed`, `completed_plan_b`, `modified`, or `skipped`
  - `main_quality`: `stable`, `minor_break`, or `clear_break`
  - `recovery_flag`: short recovery summary such as `fresh`, `normal`, `poor_sleep`, `DOMS`
  - `key_feeling`: shortest useful session feeling note
  - `next_action`: exact next-step decision for the same slot next time
  - `adjustment_reason`: why the next step changed or stayed the same

## 2026 Goals (Updated 2026-03-09)

- Bodyweight baseline: `81.5 kg`
- Height baseline: `175 cm`
- Body composition goal: reduce central fat while gaining/maintaining muscle
- Strength goal by `2026-10-01`: SBD total `250 kg`
- Running goals:
  - `10 km` in `55:00`
  - `5 km` in `24:00`
  - Full-year mileage `1000 km`
- Running progress reference:
  - Current YTD mileage: `61.6 km`
  - Remaining mileage: `938.4 km`
  - From `2026-03-09` to year-end target average: around `22.1 km/week`

## Weekly Management Checklist

- Daily:
  - morning bodyweight (same time, same condition)
  - training log append (strength/run)
- Weekly (fixed weekday, e.g. Monday morning):
  - bodyweight 7-day average
  - waist circumference
  - weekly running mileage
  - key lift completion quality (squat/bench/deadlift main work sets)
  - recovery self-check: sleep, fatigue, soreness, stress
- Adjustment triggers (for next week):
  - if bodyweight and waist both stall for 2+ weeks, tighten intake or increase easy-run volume slightly
  - if fatigue/soreness remains high for 2+ weeks, reduce accessory volume first (not main lift quality)
  - if running quality hurts lower-body strength sessions, keep strength priority and cut run intensity before cutting all run volume

## Weekly Review Template

- Review these four questions once per week:
  - Did the main lifts progress as planned, stall, or require Plan B?
  - Which movement or body area limited performance most?
  - How far was weekly run volume from target?
  - What are the only 1-2 variables to change next week?
- Review output format:
  - `main_lifts`: one line each for squat, bench, deadlift
  - `running`: total km, quality session completion, easy-run completion
  - `recovery`: bodyweight trend, waist trend, sleep, soreness, stress
  - `decision`: exact load / volume / run adjustment for next week
