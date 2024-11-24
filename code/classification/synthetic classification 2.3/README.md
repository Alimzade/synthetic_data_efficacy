# Synthetic classification 2.3

Here we add 50% more synthetic images to meningioma class. **(66% real / 33% synthetic)**

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 91%

|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.90 |     0.92 |       0.91 |
| meningioma |        0.81 |     0.84 |       0.82 |
| notumor    |        0.98 |     0.96 |       0.97 |
| pituitary  |        0.98 |     0.91 |       0.91 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.92 |     0.91 |       0.90 |
