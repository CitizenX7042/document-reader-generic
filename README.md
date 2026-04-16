# document-reader-generic

Python project scaffold. Configure `configs/config.yaml` and copy `.env.example` to `.env` for local secrets.

## Local run

From the repository root:

```bash
./scripts/run_local.sh
```

Or:

```bash
python -m src.main
```

## Layout

- `src/` — application code
- `configs/` — configuration files
- `data/` — raw, validated, and rejected inputs
- `logs/` — runtime logs
- `state/` — durable local state
- `scripts/` — helper scripts
- `tests/` — tests
