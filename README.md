# Survey on Mental Health in the Tech Workplace in 2014

- [Survey on Mental Health in the Tech Workplace in 2014](#survey-on-mental-health-in-the-tech-workplace-in-2014)
  - [Set up Environment](#set-up-environment)
  - [Pre-commit hooks installation](#pre-commit-hooks-installation)
  - [Start Notebook server](#start-notebook-server)
  - [Data](#data)
  - [TODO](#todo)

## Set up Environment

```bash
$ git clone https://github.com/ml-en-action/kaggle-mental-health-in-tech-survey.git
$ cd kaggle-mental-health-in-tech-survey
$ conda env update -f binder/environment.yml
$ conda activate ml-en-action
$ bash binder/postBuild
```

## Pre-commit hooks installation

```bash
$ pre-commit install
```

## Start Notebook server

```bash
$ conda activate ml-en-action && jupyter lab
```

## Data

- Kaggle dataset: https://www.kaggle.com/osmi/mental-health-in-tech-survey/notebooks

## TODO

- [x] Download data
- [ ] Reproduce example notebook: https://www.kaggle.com/rblcoder/mental-health-happiness-economics-human-freedom
