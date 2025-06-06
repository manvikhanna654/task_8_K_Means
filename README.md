# task_8_K_Means

This project performs unsupervised learning using **K-Means Clustering** on any uploaded CSV dataset. It's designed to work seamlessly in **Google Colab**.

## 📌 Features
- Upload your own CSV file.
- Automatically displays column names.
- Cleans dataset (removes missing values).
- Selects numeric features for clustering.
- Scales features using StandardScaler.
- Uses the **Elbow Method** to find the best number of clusters (K).
- Visualizes clusters using **PCA** (2D plot).
- Evaluates clustering quality using **Silhouette Score**.

## 🛠️ How to Use
1. Run the notebook in **Google Colab**.
2. Upload your CSV file when prompted.
3. Check the column names printed in output.
4. Adjust `optimal_k` based on the Elbow graph.
5. View clustering results and silhouette score.

## 📁 Output Includes
- Elbow Plot (K vs Inertia)
- 2D Cluster Visualization (using PCA)
- Silhouette Score (cluster evaluation)

## 📊 Requirements
- Python 3
- Libraries: `pandas`, `numpy`, `matplotlib`, `sklearn`

>  Best used with datasets like customer segmentation, housing data, or any dataset with meaningful numeric features.
