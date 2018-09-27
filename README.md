### RSR_projects

[![CircleCI](https://circleci.com/gh/dmitrybeloborodov/RSR_projects.svg?style=svg)](https://circleci.com/gh/dmitrybeloborodov/RSR_projects)

### Requirements
`pipenv` or `conda` installed

### Usage

#### To init environment:
```bash
pipenv install -r requirements.txt
```
OR
```bash
conda env create -f my_environment.yml
```

#### To convert notebook to HTML:
```bash
pipenv run jupyter nbconvert --to html "file_name.ipynb"
```
OR

```bash
(source) activate myenv
jupyter-nbconvert --to html "file_name.ipynb"
```
