# 🧠 Image Processing

Machine Learning for Fashion Recognition

## 📊 Project Overview
This project focuses on building image classification models for the **MNIST Fashion dataset**, applying various machine learning algorithms to predict fashion item categories. The goal is to optimize model performance based on accuracy, computational efficiency, and resource utilization.

## 📦 Dataset
- **Source:** [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
- **Files:**
  - `data/MNIST-fashion_training_set-49.csv`
  - `data/MNIST-fashion_testing_set-49.csv`
- **Features:**
  - `label`: Category of the fashion item.
  - `pixel_1` to `pixel_49`: Grayscale pixel values (0-255).

## 🚀 Models Implemented
- Multinomial Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Random Forest
- Ridge, Lasso, Elastic Net Regression
- Support Vector Machines (SVM)
- Gradient Boosting (XGBoost/GBM)
- Neural Networks (nnet, h2o)

## ⚙️ Evaluation Metrics
The models are evaluated using a custom scoring function:

```
Points = 0.15 * A + 0.1 * B + 0.75 * C
```
- **A:** Proportion of training data used
- **B:** Model runtime efficiency
- **C:** Misclassification rate

## 📈 Results
- Performance metrics for each model are documented in the `reports/` folder.
- Scoreboards summarize average model performance across different sample sizes.

## 📝 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MartinNgTP/Image-Processing-ML.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Image-Processing-ML
   ```
3. Open the R Markdown files in the `docs/` folder to view model implementations and analyses.

## 🌍 Live Demo
Check out the live reports [here](https://martinngtp.github.io/Image-Processing-ML/).

## 📚 Acknowledgments
- Fashion MNIST Dataset by Zalando Research
- Libraries: `caret`, `glmnet`, `randomForest`, `xgboost`, `nnet`, `h2o`, `e1071`

---

Made with ❤️ by Martin Ng

