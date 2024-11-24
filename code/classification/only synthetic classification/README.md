# Synthetic-only classification

Here we use only synthetic images, generated with diffusion model (no real image) for training classifier.

Average results and figures from 3 classification reports are in `classification_results.ipynb`.

*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*

\
\
Accuracy: 78%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.91 |     0.67 |       0.77 |
| meningioma |        0.53 |     0.79 |       0.63 |
| notumor    |        0.89 |     0.91 |       0.90 |
| pituitary  |        0.87 |     0.77 |       0.82 |



|               |  precision |  recall |  f1-score |
|:--------------|-----------:|--------:|----------:|
| Macro Average |       0.80 |    0.79 |      0.78 |