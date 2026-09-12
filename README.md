# PRODIGY_ML_04 - Hand Gesture Recognition using Random Forest

This repository contains the solution for **Task-04** of the Machine Learning Internship at **Prodigy InfoTech**.

## 📌 Project Overview
The objective of this task is to build a robust image classification model using a Random Forest Classifier to accurately identify and recognize various hand gestures from image datasets.

## 📊 Dataset Information
* **Dataset Name:** Leap Gestures Recognition Dataset (`leapGestRecog`)
* **Scale & Structure:** The complete dataset consists of **~40,000 images** distributed across **221 folders** (total size approx. **2.13 GB**), capturing different hand gestures performed by multiple subjects.
* **Note on Repository Size:** Due to the large file size (2.13 GB), raw image datasets are **not** included directly in this repository. You can download the complete dataset from Kaggle:
  * **Dataset Link:** [Leap Gesture Recognition Dataset on Kaggle](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Libraries:**
  * `cv2` (OpenCV) for image reading and grayscale conversion
  * `numpy` for array manipulation and numerical operations
  * `scikit-learn` for data splitting, Random Forest Classifier, and performance metrics

## 📊 Methodology & Steps
1. **Data Loading & Preprocessing:** Iterated through the dataset directories, loaded images in grayscale mode, resized them to uniform dimensions ($64 \times 64$ pixels), and flattened them into feature arrays.
2. **Train-Test Split:** Split the preprocessed data into 80% training and 20% testing partitions.
3. **Model Training:** Trained an ensemble **Random Forest Classifier** (`n_estimators=100`) to capture complex feature boundaries among different gesture classes.
4. **Evaluation:** Evaluated model performance using Accuracy Score, Precision, Recall, and F1-Score via a detailed Classification Report.

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone [https://github.com/pranshu998877-jpg/PRODIGY_ML_04.git](https://github.com/pranshu998877-jpg/PRODIGY_ML_04.git)
