# StakeholderValueNetworks

Run this project with `uv` on both macOS and Windows.

## Quick start

```bash
uv python install 3.12
uv sync --frozen
uv run jupyter lab StakeholderValueNetworks.ipynb
```

## Notes

- `uv.lock` is committed for reproducible installs across platforms.
- `.python-version` pins the default interpreter to Python 3.12.
- You can also open classic Notebook UI:

```bash
uv run jupyter notebook StakeholderValueNetworks.ipynb
```
