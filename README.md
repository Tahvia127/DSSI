# Data Science Summer Institute — Coursework

My worked notebooks from the **Data Science Summer Institute (DSSI) 2026** Python foundations sequence, kept as a personal reference.

> **Note:** the teaching notebooks and slide PDFs in this repository were provided by the DSSI instructors. What's mine is the work done inside the exercise cells. This repo is a learning archive, not an original project — see [PublicPath](https://github.com/Tahvia127/PublicPath) or [data-237-final-project](https://github.com/Tahvia127/data-237-final-project) for original work.

## Contents

```
notebooks/
  1-Getting_Started_with_Python_and_Colab_Notebooks.ipynb   Colab basics, cell types, arithmetic
  2-Collections_of_Data.ipynb                               Lists, tuples, sets, dicts, NumPy arrays
  3-DataFrames.ipynb                                        pandas DataFrames, indexing, grouping
  4-Conditionals_and_Loops.ipynb                            if statements, for loops, timing

reference/    Slide PDFs, including an Introduction to NLP deck
data/         AirBnB Chicago listings — the dataset used in the DataFrames notebook
```

## Topics covered

| Notebook | Concepts |
|---|---|
| 1 | Notebook environment, code vs. markdown cells, `math` module |
| 2 | Python sequences, NumPy arrays, when to use which structure |
| 3 | pandas DataFrames — rows as instances, columns as attributes, Drive mounting |
| 4 | Conditionals, `for` loops, and loop performance with `process_time` |

## Running

The notebooks were written for Google Colab. To run locally:

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install numpy pandas jupyterlab
jupyter lab
```

Notebook 3 mounts Google Drive via `google.colab`; running locally, point it at `data/AirBnB_chicago_listings.csv` instead.
