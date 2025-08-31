
# k-NN Housing Price Prediction — Submission Package

## Files to include in your GitHub folder:
- `maurrasse_mike_knn_assignment.ipynb` (the notebook)
- `synthetic_california_housing.csv` (CSV fallback dataset)
- A picture (PNG/JPG) of your manual calculations (Part 4.1)
- Exported PDF report: `maurrasse_mike_knn_report.pdf`

## How to run
1. Open the notebook in **Google Colab** or **Jupyter**.
2. By default, the notebook attempts to load the **California Housing** dataset via `sklearn.datasets.fetch_california_housing`.
3. If fetching fails (due to no internet/cache), the notebook will **automatically load `synthetic_california_housing.csv`** instead.
4. Run all cells top-to-bottom.
5. Fill in the write-up sections and do the manual calculations (Part 4). Add your hand-written calculation photo to the repo.
6. Export to PDF: `maurrasse_mike_knn_report.pdf`.

## Notes
- All plots use matplotlib.
- Custom k-NN (from scratch) with multiple distance metrics and weighting is implemented.
- Includes hyperparameter tuning with 5-fold CV, sklearn comparison, and curse-of-dimensionality demo.
