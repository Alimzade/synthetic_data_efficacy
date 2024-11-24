# Synthetic classification 2.2

Here we add 25% more synthetic images to meningioma class. **(80% real / 20% synthetic)**

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 92%

|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.98 |     0.84 |       0.90 |
| meningioma |        0.75 |     0.92 |       0.82 |
| notumor    |        1.00 |     0.99 |       0.99 |
| pituitary  |        0.96 |     0.95 |       0.95 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.92 |     0.92 |       0.92 |