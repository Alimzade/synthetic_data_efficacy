# Synthetic classification 4.2

Here we add 400 synthetic images to each class.

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 93%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.92 |     0.91 |       0.91 |
| meningioma |        0.83 |     0.84 |       0.83 |
| notumor    |        0.99 |     0.99 |       0.99 |
| pituitary  |        0.96 |     0.96 |       0.96 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.92 |     0.92 |       0.92 |
