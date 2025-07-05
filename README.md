
## Bean Classification - Kaggle Competition

This repository contains a machine learning project developed for a Kaggle competition focused on classifying different types of dry beans based on geometric features. The goal was to build an accurate classifier using structured data. The final model achieved a high accuracy of **92.941%** on the validation set.

---

## Project Members

[Mohamed Ahmed](https://github.com/mohamed-tageldeen)
[Sameh Walid](https://github.com/SamehWalidd)
[Adham Waheeb](https://github.com/waheeb4)
[Youssef Fathi]

---

## Dataset

The dataset consists of geometric measurements extracted from images of dry beans. It includes:

- `train_c.csv`: Contains labeled training samples used for model development
- `test_no_label.csv`: Contains unlabeled test samples used for prediction

Each sample includes numerical features such as area, perimeter, major axis length, compactness, and others, along with the corresponding bean type (in the training set).

---

## Project Steps

1. **Data Collection**  
   Loaded the training and test datasets into memory for processing.

2. **Data Exploration**  
   Conducted exploratory data analysis (EDA) to understand distributions, feature correlations, and class imbalances.

3. **Data Preparation**  
   Preprocessed the data through label encoding, feature scaling, and other transformations to make it suitable for machine learning models.

4. **Model Development**  
   Trained and fine-tuned multiple machine learning classification models to find the most effective one.

5. **Model Evaluation**  
   Evaluated models using performance metrics such as accuracy and confusion matrix to identify the best candidate.

6. **Prediction and Inference**  
   Applied the selected model to the test dataset to generate predictions.

7. **Result Submission**  
   Prepared a submission file containing predictions for the Kaggle competition.

---

## Results

- Final Accuracy on Validation Set: **92.941%**
- Best-performing model: (RBF SVM model) selected after comparing multiple classifiers

---



---


