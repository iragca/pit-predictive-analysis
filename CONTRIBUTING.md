# Requirements

We work with uv. You can install it [here](https://docs.astral.sh/uv/guides/install-python/)

After installing uv, run this command in the project repository root directory to install dependencies:

```bash
uv run sync   #  Install dependencies
```

To then run scripts:

```bash
uv run something.py #equivalent to python -m something.py
```

To use the environment in notebooks, simply select the `.venv` environment that was created in this repository as the kernel.

## Contributing

The main notebook is found [here](notebooks/1.0-random-useless-facts.ipynb).

These are other makefile commands for doing common tasks:

```bash
make lint           #  Lint the code
make format         #  Format the code
make docs           #  Run a local mkdocs server for documentation
make tests          #  Run unit tests
```
