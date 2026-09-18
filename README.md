# Corporate Credit Rating Lab

Student exercise in corporate credit-rating analysis and machine learning using public data.

## Setup

Install uv:

https://docs.astral.sh/uv/getting-started/installation/

Open a terminal in this folder and run:

```sh
uv sync --locked
uv run --locked jupyter lab
```

uv installs the required Python version and locked packages in a local `.venv`. You do not need to activate the environment.

Open `exercice_student_version.ipynb` in JupyterLab. Keep the notebook in the repository root because it reads `kaggle/corporate_rating.csv` by a relative path. The notebook contains exercises marked `TO DO` and will not run to completion until they are filled in.

## Dataset

The exercise uses Alan Gewerc's Corporate Credit Rating dataset:

https://www.kaggle.com/datasets/agewerc/corporate-credit-rating

The Kaggle page lists the dataset under the CC BY 4.0 license. The notebook discusses its construction and limitations.
