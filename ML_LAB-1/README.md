# ML-LAB-1: Visualization and k-NN on IRIS Dataset

## 🎯 Aim
Visualize features and implement **k-Nearest Neighbors (k-NN)** for the IRIS dataset for different values of k (1, 3, 5, 7) using **5-fold Cross Validation** with scikit-learn.

## 📖 Theory
The **Iris dataset** is a classic dataset in machine learning containing 150 samples of iris flowers from three species (*setosa*, *versicolor*, *virginica*), with four features:  
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

**k-NN Algorithm**:  
- A non-parametric, instance-based learning algorithm.
- Classifies a sample based on the majority vote of its *k* nearest neighbors.
- The value of *k* affects model performance: smaller k → more sensitive to noise; larger k → smoother decision boundaries.

**5-Fold Cross Validation**:  
- The dataset is split into 5 folds.
- Each fold is used once as a test set, and the other 4 folds form the training set.
- Accuracy is averaged over 5 iterations to reduce overfitting and bias.

## 🖥 Implementation Steps
1. Load the dataset.
2. Perform feature visualization:
   - Pairplot  
   - Boxplots  
   - Correlation heatmap
3. Implement k-NN for k = 1, 3, 5, 7 with 5-fold CV.
4. Plot **Accuracy vs k** graph.
5. Select the best k and evaluate on the test set.

## 📊 Results
- Outputs include:
  - Visualizations (pairplot, boxplots, heatmap)
  - Accuracy vs k plot
  - Classification report (Precision, Recall, F1-score)
  - Confusion matrix

## 📂 Files in this Folder
- `code.py` → Python implementation
- ` 2K23_CS_373__Sameer.pdf` → Lab report with aim, theory, code, output, and conclusion
- `ML_Lab1.ipynb` (Colab Notebook) -> https://colab.research.google.com/drive/1iqxrA0osRJposT0G8KA0urU-_cvrnAoh


