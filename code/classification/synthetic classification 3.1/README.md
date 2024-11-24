# Synthetic classification 3.1

Here we add 11% more synthetic images to meningioma and glioma classes. **(90% real / 10% synthetic)**

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 93%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.93 |     0.90 |       0.92 |
| meningioma |        0.81 |     0.86 |       0.83 |
| notumor    |        0.99 |     0.99 |       0.99 |
| pituitary  |        0.96 |     0.96 |       0.96 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.92 |     0.93 |       0.92 |
