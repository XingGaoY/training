# Training Notes

## Profile

- Name: `zhen`
- Sex: female
- Birth: `1995-03`
- Height baseline: `165 cm`
- Add baseline bodyweight and goals here.

## Training Caution

- Previously used the same program as `xinggao`.
- Post-training symptoms reported: palpitations / irregular heartbeat sensation / nerve-jumping sensation.
- Completed hospital workup: Holter, echocardiogram, treadmill stress test.
- Holter detail provided later: `24h` recording, `single PVCs 9225 times`.
- Observed trigger: symptoms did not recur when bench press was removed.
- Additional fact: bench press at `20 kg` does not trigger the symptoms.

## Current Program Facts

- Current structure: `1` split with upper-body-emphasis and lower-body-emphasis days alternating.
- Same exercise list is retained across both days.
- The emphasis changes by load and volume.

### Upper-Body-Emphasis Day

- 深蹲: `20kg x 12 x 3`
- 杠铃罗马尼亚硬拉: `20kg x 12 x 3`
- 宽距高位下拉: `13.5kg x 6 x 2`, `13.5kg x 12 x 3`
- 坐姿划船: `22.5kg x 12 x 3`, `22.5kg x 10 x 1`
- 哑铃卧推: `(5+5)kg x 12 x 1`, `(7.5+7.5)kg x 8 x 2`, `(5+5)kg x 12 x 1`
- 面拉: `2.5kg x 12 x 3`
- 弹力带一侧拉: `2.5kg x 12 x 3`

### Lower-Body-Emphasis Day

- 深蹲热身: `20kg x 8`, `25kg x 5`, `27.5kg x 1`
- 深蹲正式组: `30kg x 5 x 3`
- 杠铃罗马尼亚硬拉热身: `20kg x 8`, `25kg x 5`, `30kg x 1`
- 杠铃罗马尼亚硬拉正式组: `27.5kg x 5 x 1`, `25kg x 8 x 2`
- 宽距高位下拉: `9.5kg x 6 x 3`
- 坐姿划船: `9.5kg x 8 x 3`
- 哑铃卧推: `(5+5)kg x 8 x 2`
- 面拉: `2.5kg x 12 x 3`
- 弹力带一侧拉: `2.5kg x 12 x 3`

## Suggested Program Version

- Keep the same exercise pool.
- Keep the upper-body-emphasis / lower-body-emphasis alternating structure.
- Reduce non-priority volume on each day so the emphasis is clearer.

### Suggested Upper-Body-Emphasis Day

- 深蹲: `20kg x 10-12 x 2`
- 杠铃罗马尼亚硬拉: `20kg x 10-12 x 2`
- 宽距高位下拉: `13.5kg x 8-12 x 4`
- 坐姿划船: `22.5kg x 8-12 x 4`
- 哑铃卧推: `(5+5)kg x 10-12 x 1`, `(7.5+7.5)kg x 6-8 x 2`, `(5+5)kg x 10-12 x 1`
- 面拉: `2.5kg x 12-15 x 3`
- 弹力带一侧拉: `2.5kg x 12-15 x 2-3`

### Suggested Lower-Body-Emphasis Day

- 深蹲热身: `20kg x 8`, `25kg x 5`, `27.5kg x 1`
- 深蹲正式组: `30kg x 5 x 3`
- 杠铃罗马尼亚硬拉: `27.5kg x 5 x 1`, `25kg x 8 x 2`
- 宽距高位下拉: `9.5kg x 8-10 x 2-3`
- 坐姿划船: `9.5kg x 8-10 x 2-3`
- 哑铃卧推: `(5+5)kg x 8-10 x 2`
- 面拉: `2.5kg x 12-15 x 2`

### Suggested Progression Notes

- 深蹲、杠铃罗马尼亚硬拉、宽距高位下拉、坐姿划船: complete the top of the rep range before increasing load.
- 面拉、弹力带一侧拉: prioritize stable execution before increasing load.
- 哑铃卧推: progress separately from the other lifts.

## Logging Rules

- CSV is the only historical source of truth.
- Logs are append-only whenever possible.
- Week format: `YYYY-Www` (example: `2026-W10`).
- This note file and all related CSV logs belong to `training/people/zhen/`.
- Planned sessions should also be recorded in `plan_log.csv`.
- In `body_check_log.csv`, `cardiac_symptom_flag` should record simple daily status such as `none`, `during_training`, `post_training`, or another short factual tag.
- Post-training reporting format should match `xinggao`:
  - what was done
  - rest time
  - RPE
  - subjective feeling
