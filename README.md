Here's an example of using DenseNet264 to train and test QC models for various artifact categories like Noise, Zipper, Positioning, Banding, Motion, Contrast, and Distortion. This serves as the baseline implementation for Task 1 of the LISA 2024 Challenge. The training data were split into two groups—training and validation—using Excel files named "training_cohort_Distortion.xlsx" and "validation_cohort_Distortion.xlsx". The best model from training is then applied to a separate test group using a testing script.
