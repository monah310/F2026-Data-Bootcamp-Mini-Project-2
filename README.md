# F2026-Data-Bootcamp-Mini-Project-2
We compared Ridge regression using grouped PCA features with histogram gradient boosting using the original predictors, where both used the same 80/20 split (random_state=42) and five-fold cross-validation in the training portion.
| Model | Recorded validation RMSE |
| --- | ---: |
| Ridge with PCA summaries | $34,681.74 |
| Histogram gradient boosting | $29,499.88 |

We selected gradient boosting after it reduced validation RMSE by about 14.94%.
**Files and reproduction**
- Copy_of_Regression_Competition.ipynb: original code.
- Regression_Competition_Commentary: code adjusted for readability and number reporting with added commentary.
- data/README.md: required competition files and data placement.
1. Install Python.
2. Put the original competition train.csv, test.csv, and solns.csv in data/.
3. Run jupyter lab from this folder, open the notebook, and run all cells in order.
4. The notebook writes outputs/the_new_winning.csv without uploading it anywhere.
In Colab, upload or mount the data and update DATA_DIR.
Raw competition data, the submitted prediction file, and the Kaggle score are not included here.
