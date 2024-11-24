# Synthetic classification 3.3

Here we add 50% more synthetic images to meningioma and glioma classes. **(66% real / 33% synthetic)**

Average results and figures from 3 classification reports are in `classification_results.ipynb`.


*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 91%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.98 |     0.83 |       0.89 |
| meningioma |        0.72 |     0.91 |       0.80 |
| notumor    |        0.98 |     0.99 |       0.98 |
| pituitary  |        0.95 |     0.92 |       0.94 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.91 |     0.91 |       0.90 |
