# 33/66 mix classification


Here we only use 33/66 mix of real and generated images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 74.67% ± 3.21%
|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.77 ± 0.08 | 0.61 ± 0.22 | 0.65 ± 0.13 |
| meningioma | 0.52 ± 0.11 | 0.58 ± 0.21 | 0.53 ± 0.07 |
| notumor    | 0.89 ± 0.10 | 0.92 ± 0.03 | 0.90 ± 0.04 |
| pituitary  | 0.83 ± 0.03 | 0.87 ± 0.01 | 0.85 ± 0.02 |




|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.75 |     0.74 |       0.73 |

