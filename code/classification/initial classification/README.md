# Initial classification


Here we only use real pre-processed images (no synthetic image) for training classifier.


Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 93%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.93 |     0.91 |       0.93 |
| meningioma |        0.83 |     0.88 |       0.86 |
| notumor    |        0.98 |     0.99 |       0.98 |
| pituitary  |        0.98 |     0.94 |       0.96 |



|               |  precision |  recall |  f1-score |
|:--------------|-----------:|--------:|----------:|
| Macro Average |       0.93 |    0.93 |      0.93 |