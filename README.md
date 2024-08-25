# Blood Pressure Estimation

## Introduction

A playground on estimating blood pressure based on PPG signals associated with demographic data obtained from hundereds of cases.

## Setup

Set up the environment.

```shell
python3 -m venv env
source env/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

On Ubuntu operating system, just run `setup.sh`, and then you can launch *JupyterLab*

```bash
jupyter lab
```

to explore the project.

**Note**: If you have installed new dependencies, please freeze them into `requirements.txt` for future use:

```shell
pip3 freeze > requirements.txt
```

## Requirements

```
pip3 install numpy pandas openpyxl tqdm matplotlib jupyterlab scipy pyampd mrmr_selection mat73 tensorflow pydot scikit-learn sklearn_relief seaborn pycaret[analysis]
```

## License

This project has been released under *MIT License*.
