# 50/50 mix classification


Here we only use 50/50 mix of real and generated images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 71.67% ± 3.06%

|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.77 ± 0.08 | 0.48 ± 0.16 | 0.58 ± 0.10 |
| meningioma | 0.45 ± 0.04 | 0.62 ± 0.03 | 0.53 ± 0.01 |
| notumor    | 0.89 ± 0.01 | 0.92 ± 0.05 | 0.90 ± 0.03 |
| pituitary  | 0.82 ± 0.06 | 0.88 ± 0.05 | 0.73 ± 0.18 |


|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.73 |     0.72 |       0.68 |
