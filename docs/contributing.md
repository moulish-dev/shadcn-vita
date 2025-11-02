# Contributing

Fork and clone the repo  
Create a venv and install dev deps:

    :::python
    pip install -e .
    pre-commit install

Create a feature branch, add tests if applicable.

Run formatting/lint:

    :::python
    ruff check . && ruff format .
    pytest -q

Open a PR with a clear description & screenshots/audio when relevant

