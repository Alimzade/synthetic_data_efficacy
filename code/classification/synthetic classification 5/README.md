# Fine-Tuning with Synthetic Images
\
`Here we first train a classifier only with original images (no synthetic image).`

Avg. Initial Classifier Performance:

---
\
Accuracy: 93%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.91 |     0.95 |       0.93 |
| meningioma |        0.86 |     0.82 |       0.84 |
| notumor    |        0.98 |     0.99 |       0.99 |
| pituitary  |        0.97 |     0.95 |       0.96 |


|               |  precision |  recall |  f1-score |
|:--------------|-----------:|--------:|----------:|
| Macro Average |       0.93 |    0.93 |      0.93 |

\
\
`Then we fine-tune initial model on combined set of original glioma and meningioma images + all synthetic images for 3 more epochs. `

Avg. Fine-Tuned Classifier Performance:

-----
\
Accuracy: 93%
|            |   precision |   recall |   f1-score |
|:-----------|------------:|---------:|-----------:|
| glioma     |        0.95 |     0.90 |       0.92 |
| meningioma |        0.84 |     0.84 |       0.83 |
| notumor    |        0.98 |     0.99 |       0.98 |
| pituitary  |        0.94 |     0.97 |       0.96 |


|               |  precision |  recall |  f1-score |
|:--------------|-----------:|--------:|----------:|
| Macro Average |       0.93 |    0.93 |      0.93 |
---
\
\
The idea behind mixing real and synthetic data for fine-tuning is to help the model learn additional features or variations present in the synthetic data while reinforcing the patterns learned from the real data. 

\
\
*Each report obtained using different seeds (33, 66, 99) for random number generators in numpy and tensorflow operations.*