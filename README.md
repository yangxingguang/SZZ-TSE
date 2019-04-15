# SZZ-TSE
This repository proposes the supplementary materials for our paper - The Impact of Changes Mislabeled by SZZ on Just-in-Time Defect Prediction.

## How to run
* Clone the code to a directory
* Modify a line in the file `code/calculation/classification_importance.R`, the line is as follows:
```
# Specify the Directory of the path storing the project
# DIR_PATH = "?"
DIR_PATH = "" 
```
* Create the following directories in `data_results/`: `importance`, `oneway`, `results_imbalance`, `results_balance`.
* Run the script `code/calculation/classification_importance.R`

## Results
The results will be stored in `data_results/importance/`, `data_results/oneway/`,  `data_results/results_imbalance/`, `data_results/results_balance/` after running the script. We store the performance scores (e.g., auc) in each of the 1,000 bootstrap iterations into csv files.
