# 2nd mini classification


Here we use 216 real images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 80.33% ± 1.53%

|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.86 ± 0.03 | 0.67 ± 0.01 | 0.76 ± 0.01 |
| meningioma | 0.57 ± 0.02 | 0.68 ± 0.05 | 0.62 ± 0.02 |
| notumor    | 0.93 ± 0.05 | 0.95 ± 0.02 | 0.94 ± 0.02 |
| pituitary  | 0.84 ± 0.01 | 0.92 ± 0.03 | 0.88 ± 0.01 |


|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |         0.8 |      0.8 |        0.8 |

