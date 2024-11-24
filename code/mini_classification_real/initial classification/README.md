# Initial mini classification


Here we only use 72 (18 per class) real images (no synthetic image) for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 62.00% ± 7.55%
|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.63 ± 0.19 | 0.50 ± 0.38 | 0.46 ± 0.17 |
| meningioma | 0.41 ± 0.03 | 0.52 ± 0.30 | 0.42 ± 0.14 |
| notumor    | 0.87 ± 0.09 | 0.81 ± 0.05 | 0.84 ± 0.06 |
| pituitary  | 0.83 ± 0.09 | 0.66 ± 0.35 | 0.67 ± 0.25 |


|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.69 |     0.62 |        0.6 |
