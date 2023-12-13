# Huggin-face compute

## Installation
Be sure to execute this from a non-venv shell

```shell
git clone git@github.com:ia-remix/hugging-play.git
cd hugging-play
virtualenv venv
source .venv/bin/activate
pip install poetry
poetry install
```

## Commands

### Tools
- Check lint

```shell
poetry run ruff src 
```

- Fix code formatting
```shell
poetry run black src 
```

## Package management
Poetry: https://python-poetry.org/

## Quality

### Tools
#### Linter
Ruff: https://docs.astral.sh/ruff/

#### Prettier
Black: https://black.readthedocs.io/en/stable/


## Recommended IDE PyCharm Configuration
### Plugins
Ruff: Settings > Plugins > Marketplace > "Ruff"

### Actions on save
Black: Settings > Tools > Black
- On Code Reformat
- On save
  both need to be checked.

### File nesting
Project tool window | '...' (vertical) | "File Nesting..."
Set (click on the '+' sign)
- 'Parent File Suffix': '.py'
- 'Child File Suffix': '_spec.py'

