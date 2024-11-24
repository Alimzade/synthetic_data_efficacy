# 10/90 mix classification


Here we only use 10/90 mix of real and generated images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 78.33% ± 2.52%
|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.89 ± 0.03 | 0.58 ± 0.11 | 0.70 ± 0.07 |
| meningioma | 0.53 ± 0.04 | 0.74 ± 0.04 | 0.62 ± 0.02 |
| notumor    | 0.94 ± 0.01 | 0.93 ± 0.03 | 0.93 ± 0.02 |
| pituitary  | 0.84 ± 0.03 | 0.91 ± 0.04 | 0.87 ± 0.01 |



|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |         0.8 |     0.79 |       0.78 |

