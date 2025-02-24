# Machine Learning Algorithms

This repository contains the implementation of three fundamental machine learning algorithms: **K-Nearest Neighbors (KNN), K-Means Clustering, and Binary Logistic Regression**. Each algorithm is applied to different datasets, and the results are analyzed to evaluate their performance.

## Algorithms and Implementations

### 1. K-Nearest Neighbors (KNN)

- **Classification**: Applied to the **Iris dataset** to classify flower species.
- **Regression**: Applied to the **Diabetes dataset** to predict disease progression.
- **Results**:
  - **Classification**: Achieved a test accuracy of **96.667%** for K=1, 3, 5, and 15.
  - **Regression**: Achieved the best **Mean Squared Error (MSE) of 3396.39** for K=5.

### 2. K-Means Clustering

- Applied to a **2D dataset** to group data points into clusters.
- **Results**:
  - Evaluated for K=2, 4, 6, and 7.
  - The optimal number of clusters was determined using the **elbow method**, with **K=4 or K=6** providing the best balance between inertia and overfitting.

### 3. Binary Logistic Regression

- Applied to the **Diabetes dataset** for binary classification.
- **Results**:
  - Achieved a **validation accuracy of 81.82%** with a learning rate of **0.1**.
  - Achieved a **test accuracy of 77.61%**, demonstrating the model's capability to handle medical data.

**Note:** The results mentioned above were obtained during the first run. Your results may differ when running the implementation on your own device due to variations in hardware, software environment, or dataset updates.

## How to Use

### Clone the Repository:

```bash
git clone https://github.com/neyamul-hasan14/Machine-Learning-Algorithms.git
```

### Navigate to the Desired Algorithm:

- **For KNN**, go to the `KNN/` directory.
- **For K-Means**, go to the `KMeans/` directory.
- **For Logistic Regression**, go to the `Logistic_Regression/` directory.

### Run the Jupyter Notebooks:

- Each directory contains a Jupyter Notebook (`*.ipynb`) with the implementation and analysis of the respective algorithm.
- Open the notebook using **Jupyter Notebook** or any compatible IDE to explore the code and results.

## Dependencies

### Required Libraries:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib



### Install the required libraries using:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Conclusion

This repository provides a comprehensive implementation of three key machine learning algorithms. The results demonstrate the effectiveness of each algorithm in handling different types of data and tasks. The repository is structured to be easy to navigate and understand, making it a valuable resource for learning and applying machine learning techniques.

