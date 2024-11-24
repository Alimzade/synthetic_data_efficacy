# This directory contains all the classifiers and results for smaller original train set.

Approaches we tried:

* `Initial Classification` - trained only on **72** images from original dataset (18 per class).
* `Synthetic Only Classification` - trained only on synthetic images.
* `1st mix` - 50/50 mix of real and synthetic images. Total of 144 images for training.
* `2nd mix` - 33/66 mix of real and synthetic images. Total of 216 images for training.
* `3rd mix` - 20/80 mix of real and synthetic images. Total of 360 images for training.
* `4th mix` - 10/90 mix of real and synthetic images. Total of 720 images for training.

\
Test set is constant across all above classifiers. Contains only pre-processed original data.


---
\
*Models were trained on 3 seeds each, and final results were obtained by averaging outputs.*