# Fitness Training Project (Offline Git + CSV)

This repository tracks training with local Git and append-only CSV logs.

## Structure

```text
training/
  people/
    xinggao/
      data/
        body_check_log.csv
        plan_log.csv
        strength_log.csv
        strength_pr.csv
        run_log.csv
      notes/
        training_notes.md
    zhen/
      data/
        body_check_log.csv
        plan_log.csv
        strength_log.csv
        strength_pr.csv
        run_log.csv
      notes/
        training_notes.md
scripts/
```

## Daily Workflow

1. Append new rows in the correct person's folder after each training session.
2. Keep history append-only whenever possible.
3. Commit with:

```bash
git add training/people/*/data/*.csv training/people/*/notes/*
git commit -m "log: YYYY-MM-DD training update"
```

## Source of Truth

- Historical training facts and PRs must come from the person's CSV files in `training/people/<name>/data/`.
- Planned sessions and completion status should be tracked in that person's `plan_log.csv`.
- Use each person's `plan_log.csv` to connect plan, actual completion, recovery notes, and next-step decisions.
- Do not invent history outside CSV + current user message context.
