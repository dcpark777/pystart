# pystart

Template repository for Python projects.
- Python version: 3.12
- Environment management: conda (miniconda)
- Build tool: poetry
- Formatter: black
- Linters:
    - flake8
    - pylint


## Getting started

### Setup Conda

For MacOS, install using homebrew: https://formulae.brew.sh/cask/miniconda
```
$ brew install --cask miniconda
```

Create Python 3.12 conda environment
```
$ conda create -n pystart python=3.12 -y
```

Initialize Conda shell
```
$ conda init bash
```
- Restart your terminal after this step

Start conda environment
```
$ conda activate pystart
```

Verify conda environment's Python version
```
$ python --version

> Python 3.12.4
```

### Setup Poetry

Install poetry
```
$ curl -sSL https://install.python-poetry.org | python3 -
```

Verify installation
```
$ poetry --version
```

Initialize poetry project
```
$ poetry init
```