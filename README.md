# General Information

This repository holds the basic directory layout for new python projects. Additional to a reasonable minimum of features (setup.cfg, requirements.txt, directory structure, ...) it contains the following extras:

- basic unittest
- easy run by `python -m package_name`

## Usage

- Rename directory `package_name`
- Edit `setupy.cfg`: replace dummy data with real data
- Run package by `python -m package_name`

## Publishing on pypi

1. Register your account on [PyPI](https://pypi.org/account/register/)
2. `pip install build twine`
3. `python -m build`
4. `twine upload -r testpypi dist/*`
