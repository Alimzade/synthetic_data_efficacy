# Exploring the Efficacy of Synthetic Data in MRI-Based Brain Tumor Classification

## Abstract
Deep learning has advanced medical image classification but remains heavily reliant on large, diverse datasets, posing ethical and practical challenges. This study investigates the role of synthetic data, generated using Denoising Diffusion Probabilistic Models (DDPM), to address data scarcity in brain tumor MRI classification. Synthetic images were evaluated for fidelity and diversity using Frechet Inception Distance (FID) and Inception Scores (IS), demonstrating high quality for specific classes. A modified VGG-19 CNN classified MRIs into glioma, meningioma, pituitary, and no tumor classes. Experiments with varying real-to-synthetic data ratios revealed that synthetic data can enhance precision and recall for certain classes, though often at the cost of accuracy and generalization. Performance peaked at specific ratios, indicating an optimal balance between real and synthetic data. Fine-tuning with combined datasets improved metrics for underrepresented classes but yielded results comparable to models trained solely on real data. These findings underscore the potential of synthetic data to augment medical imaging datasets and address data scarcity while emphasizing the importance of balanced integration. Future research should focus on validating synthetic data through expert review, refining its quality, and testing its applicability across diverse datasets.


## Contributors
- **Meher Aisha** - Carried out introductory research and background study.
- **Emily Vorderwülbeke** - Conducted data analysis and preprocessing.
- **Anar Alimzade** - Developed and implemented generative and classification models across all experimental setups.
- **Hadi Sulaiman** - Performed evaluation and interpretation of results.

## Details

This study was conducted as part of the **"Data Science Lab"** course at the **University of Passau**. It investigates the **effectiveness of synthetic data augmentation** in the classification of brain tumor types using the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).


![project_ddpm](https://github.com/user-attachments/assets/f54bc6f7-4df4-4008-853a-c7172f017f43)
