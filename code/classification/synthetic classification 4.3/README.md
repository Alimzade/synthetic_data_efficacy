# Synthetic classification 4.3

Here we add 600 synthetic images to each class.

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 93%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.95 |     0.90 |       0.92 |
| meningioma |        0.81 |     0.89 |       0.85 |
| notumor    |        0.98 |     0.99 |       0.98 |
| pituitary  |        0.97 |     0.95 |       0.96 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.93 |     0.93 |       0.93 |
