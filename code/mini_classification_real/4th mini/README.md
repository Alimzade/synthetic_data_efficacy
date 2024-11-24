# 4th mini classification


Here we use 720 real images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 85.67% ± 1.53%

|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.88 ± 0.04 | 0.78 ± 0.06 | 0.82 ± 0.02 |
| meningioma | 0.64 ± 0.05 | 0.79 ± 0.08 | 0.71 ± 0.03 |
| notumor    | 0.95 ± 0.03 | 0.97 ± 0.02 | 0.96 ± 0.01 |
| pituitary  | 0.96 ± 0.01 | 0.90 ± 0.03 | 0.93 ± 0.02 |


|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.86 |     0.86 |       0.85 |

