# 1st mini classification


Here we use 144 real images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 75.33% ± 2.08%
|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.71 ± 0.02 | 0.68 ± 0.10 | 0.69 ± 0.05 |
| meningioma | 0.55 ± 0.07 | 0.49 ± 0.06 | 0.51 ± 0.01 |
| notumor    | 0.92 ± 0.09 | 0.91 ± 0.06 | 0.91 ± 0.03 |
| pituitary  | 0.82 ± 0.08 | 0.90 ± 0.05 | 0.86 ± 0.02 |



|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.75 |     0.74 |       0.74 |