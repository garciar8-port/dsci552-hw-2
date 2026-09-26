# DSCI 552 - Homework 2

Rodrigo Garcia · GitHub: garciar8-port

The executed notebook answers questions 1(a-j), 2, and 3. The dataset is included, so no download is needed to run the analysis.

## Run locally

The dependency versions in `requirements.txt` match the environment used for verification (Python 3.12.5).

From this directory (the root of the submitted assignment repository):

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m ipykernel install --user --name dsci552-hw2 --display-name "Python (DSCI 552 HW2)"
python -m notebook Garcia_Rodrigo_HW2.ipynb
```

On Windows, activate with `.venv/Scripts/activate` in Git Bash or `.venv/Scripts/Activate.ps1` in PowerShell. Select **Python (DSCI 552 HW2)**, restart the kernel, run all cells, and save the notebook with its outputs.

## Files

- `Garcia_Rodrigo_HW2.ipynb`: analysis, written answers, tables, and figures.
- `requirements.txt`: pinned analysis and local Jupyter dependencies.
- `data/CCPP/Folds5x2_pp.xlsx`: supplied workbook; only Sheet1 is used.
- `data/CCPP/Readme.txt`: original dataset description and paper references.

The notebook uses paths relative to this directory and random seed 552.

