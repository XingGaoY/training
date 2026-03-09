# Fitness Training Project (Offline Git + CSV)

This repository tracks training with local Git and append-only CSV logs.

## Structure

```text
training/
  data/
    strength_log.csv
    strength_pr.csv
    run_log.csv
  notes/
    training_notes.md
scripts/
```

## Daily Workflow

1. Append new rows after each training session.
2. Keep history append-only whenever possible.
3. Commit with:

```bash
git add training/data/*.csv training/notes/*
git commit -m "log: YYYY-MM-DD training update"
```

## Source of Truth

- Historical training facts and PRs must come from CSV files in `training/data/`.
- Do not invent history outside CSV + current user message context.
