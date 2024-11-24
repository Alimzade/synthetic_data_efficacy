# Synthetic classification 4.1

Here we add 200 synthetic images to each class.

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 91%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.92 |     0.92 |       0.92 |
| meningioma |        0.80 |     0.84 |       0.81 |
| notumor    |        0.97 |     0.99 |       0.98 |
| pituitary  |        0.96 |     0.89 |       0.92 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.91 |     0.91 |       0.91 |
