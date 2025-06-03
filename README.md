
 K-Nearest Neighbors (KNN) Classification

##  Objective
The goal of this task is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**. The project includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

---

##  Tools & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn (sklearn)
- Matplotlib
- Seaborn

---

##  Dataset
- **Dataset Used**: Iris Dataset
- **Source**: Built-in dataset from `sklearn.datasets`

---

## Steps Followed

1. **Data Loading**  
   Loaded the Iris dataset using `sklearn.datasets.load_iris`.

2. **Data Preprocessing**  
   - Normalized features using `StandardScaler` to ensure all attributes are on the same scale.

3. **Model Building**  
   - Implemented KNN using `KNeighborsClassifier` from `sklearn.neighbors`.
   - Experimented with different values of **K (1–10)** to observe changes in accuracy.

4. **Model Evaluation**  
   - Evaluated the model using **accuracy score** and **confusion matrix**.
   - Visualized the confusion matrix using Seaborn heatmap.

5. **Dimensionality Reduction & Visualization**  
   - Reduced the 4D feature space to 2D using **PCA**.
   - Plotted **decision boundaries** to visualize how KNN separates different classes.

---

##  Output Visualization
- Accuracy scores for different K values
- Confusion matrix heatmap
- 2D decision boundary plot showing classification regions for KNN

---

##  What I Learned

- How the **K-Nearest Neighbors algorithm** works and its applications in classification.
- The importance of **feature scaling** (normalization) in distance-based algorithms like KNN.
- How to select the optimal value of **K** and analyze its impact on model performance.
- How to use **PCA** to reduce dimensionality for visualization.
- How to **evaluate models** using confusion matrices and accuracy.
- The role of **Euclidean distance** and other distance metrics in KNN.
- How to create **decision boundary plots** to visualize model behavior in 2D.

---
