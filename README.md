# Order Notebook

This folder contains `order.ipynb`, a Jupyter Notebook for the Order workflow.

## Requirements

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab
- The Python packages imported by `order.ipynb`

## Setup

Create and activate a virtual environment, then install the notebook's dependencies:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
source .venv/bin/activate
```

Install Jupyter and any packages required by the notebook:

```bash
python -m pip install --upgrade pip
python -m pip install jupyter
```

## Run the notebook

From this folder, start Jupyter:

```bash
jupyter notebook order.ipynb
```

You can also open it in JupyterLab:

```bash
jupyter lab order.ipynb
```

Run the notebook cells from top to bottom. Update any input paths, configuration values, or credentials required by the cells before execution.

## Notes

- Keep sensitive values such as passwords, API keys, and tokens out of the notebook.
- Verify that required input files are available at the paths expected by the notebook.
- Restart the kernel and run all cells when checking that the notebook works from a clean state.
