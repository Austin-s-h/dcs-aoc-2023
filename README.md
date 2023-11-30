# Advent of Code 2023

As part of the DCS group at Vertex, I'll be competing in the 2023 Advent of Code. Each day, a coding challenge is released. I'll be attempting my solutions using Python.

## Installation

```bash
python -m venv .venv
source .venv/bin/activate
poetry install --with dev
poetry build
pip install dist/dcs_aoc_2023-0.1.0-py3-none-any.whl
```

## Testing

Runs tests for each day

```bash
pytest tests
```