# Dataset

This project uses the **Diabetes 130-US hospitals** dataset from the UCI Machine Learning Repository.

## Download

1. Go to the [UCI dataset page](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008+Data).
2. Download `diabetic_data.csv` (or the archive's equivalent raw file).
3. Save it in this folder as:

```
data/diabetic_data_initial.csv
```

The notebook `scripts/Analysis.ipynb` expects that exact filename.

Processed outputs (train/test splits, balanced sets, etc.) are written to `data/artifacts/` when you run the notebook.

## Citation

If you use this dataset, cite the UCI repository and the original Strack et al. publication listed on the dataset page.

## Note

CSV files in `data/` are not tracked in git (see root `.gitignore`). Download the data locally before running the notebook.
