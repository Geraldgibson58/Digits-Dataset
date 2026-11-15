# Handwritten Digit Recognition Using Machine Learning

## Project Overview
This project applies supervised machine learning to recognize handwritten digits (0–9) using image classification. Three classification algorithms—K-Nearest Neighbors (KNN), Support Vector Classifier (SVC), and Gaussian Naive Bayes (GaussianNB)—are trained, evaluated, and optimized to determine the most accurate model.

## Dataset
The project uses the Optical Recognition of Handwritten Digits dataset, containing 5,620 handwritten digit images.

- **Training images:** 3,823
- **Testing images:** 1,797
- **Features:** 64 pixel values per image (8×8)
- **Target classes:** Digits 0–9

## Methodology
1. Load and explore the handwritten digit dataset.
2. Prepare training, validation, and testing datasets.
3. Train KNN, SVC, and GaussianNB classifiers.
4. Evaluate model performance using accuracy, precision, recall, and F1 scores.
5. Optimize hyperparameters using GridSearchCV.
6. Compare classification results and identify the best-performing model.

## Model Performance

| Model | Test Accuracy |
|---|---|
| Support Vector Classifier (SVC) | **98.27%** |
| K-Nearest Neighbors (KNN) | 98.00% |
| Gaussian Naive Bayes (GaussianNB) | 86.25% |

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Findings
The Support Vector Classifier achieved the highest classification accuracy at **98.27%**, correctly identifying 1,766 of 1,797 test images. Hyperparameter tuning improved model performance, demonstrating the importance of model optimization and comparative evaluation.

## Conclusion
This project demonstrates how supervised machine learning can automate handwritten digit recognition. The results identify SVC as the most effective classifier among the three evaluated models, highlighting its potential application in postal mail sorting, document processing, and optical character recognition systems.

## Reference
[Scikit-learn: Optical Recognition of Handwritten Digits](https://scikit-learn.org/stable/datasets/toy_dataset.html#optical-recognition-of-handwritten-digits-dataset)
