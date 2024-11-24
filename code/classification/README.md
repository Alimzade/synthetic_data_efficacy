# This directory contains all the classifiers and results.

Approaches we tried:

* `Initial Classification` - trained only on pre-processed original dataset.
* `Synthetic Only Classification` - trained only on synthetic images, generated per each class.
* `Synthetic Classification 1` - trained on balanced set, obtained by adding synthetic images to underrepresented classes of original set.
* `Synthetic Classification 2 (2.1, 2.2, 2.3)` - trained on real images + different proportions of synthetic meningioma images.
* `Synthetic Classification 3 (3.1, 3.2, 3.3)` - trained on real images + different proportions of synthetic meningioma and glioma images.
* `Synthetic Classification 4 (4.1, 4.2, 4.3)` - trained on real images + specific amounts of synthetic images added to each classes.
* `Synthetic Classification 5` - fine-tuning classifier on a combined dataset of original meningioma, glioma images and all generated (synthetic) images.

\
Test set is constant across all above classifiers. Contains only pre-processed original data.


---
\
*Models were trained on 3 seeds each, and final results were obtained by averaging outputs.*