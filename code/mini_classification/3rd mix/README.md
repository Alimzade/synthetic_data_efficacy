# 20/80 mix classification


Here we only use 20/80 mix of real and generated images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 75.00% ± 1.00%
|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.88 ± 0.05 | 0.53 ± 0.09 | 0.66 ± 0.07 |
| meningioma | 0.49 ± 0.02 | 0.74 ± 0.12 | 0.58 ± 0.03 |
| notumor    | 0.92 ± 0.02 | 0.92 ± 0.01 | 0.92 ± 0.01 |
| pituitary  | 0.83 ± 0.06 | 0.85 ± 0.03 | 0.84 ± 0.04 |




|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.78 |     0.76 |       0.75 |

