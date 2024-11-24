# Synthetic classification 2.1

Here we add 11% more synthetic images to meningioma class. **(90% real / 10% synthetic)**

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 92%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.94 |     0.88 |       0.90 |
| meningioma |        0.81 |     0.85 |       0.82 |
| notumor    |        0.98 |     0.99 |       0.98 |
| pituitary  |        0.97 |     0.96 |       0.97 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.92 |     0.92 |       0.92 |

