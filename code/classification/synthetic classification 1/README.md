# Synthetic classification 1

Here we add synthetic images to 3 least represented classes: glioma, pituitary and notumor to create a balanced set with 867 images in each class.

Average results from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 91%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.92 |     0.87 |       0.89 |
| meningioma |        0.78 |     0.85 |       0.81 |
| notumor    |        0.99 |     0.99 |       0.99 |
| pituitary  |        0.93 |     0.95 |       0.96 |

|               |   precision |   recall |   f1-score |
|:--------------|------------:|---------:|-----------:|
| Macro Average |        0.91 |     0.91 |       0.91 |