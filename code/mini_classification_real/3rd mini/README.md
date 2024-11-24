# 3rd mini classification


Here we use 360 real images for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 83.33% ± 0.58%

|            | precision   | recall      | f1-score    |
|:-----------|:------------|:------------|:------------|
| glioma     | 0.83 ± 0.06 | 0.78 ± 0.07 | 0.79 ± 0.01 |
| meningioma | 0.65 ± 0.03 | 0.66 ± 0.14 | 0.65 ± 0.06 |
| notumor    | 0.97 ± 0.03 | 0.95 ± 0.02 | 0.96 ± 0.01 |
| pituitary  | 0.89 ± 0.06 | 0.93 ± 0.06 | 0.91 ± 0.01 |


|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.83 |     0.83 |       0.83 |


