Oasis Infobyte — Data Analytics Internship (Level 1)
=====================================================

This folder contains complete Jupyter notebooks for **Level 1**.

Minimum rule: finish **at least 3 tasks**. For a Letter of Recommendation, complete as many tasks as possible from both levels.

Level 1 notebooks
-----------------
1. `notebooks/Task1.ipynb` — EDA on retail sales
2. `notebooks/Task2.ipynb` — Customer segmentation (RFM + K-Means)
3. `notebooks/Task3.ipynb` — Data cleaning
4. `notebooks/Task4.ipynb` — Sentiment analysis

How to run
----------
```bash
pip install -r requirements.txt
python scripts/generate_datasets.py
jupyter notebook notebooks
```

Open each notebook and run **Cell → Run All**. Datasets live in `data/raw/`. Cleaned output from Task 3 is saved to `data/cleaned/`.

Notes
-----
Datasets are generated locally so you do not need a Kaggle account. They follow the same structure as typical Kaggle retail / e-commerce / review datasets named in the internship brief.
