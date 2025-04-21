## 📊 Self-Organizing Map (SOM) on Iris Dataset

This project demonstrates the use of a Self-Organizing Map (SOM) to cluster and visualize the Iris dataset using the `MiniSom` Python library.

### 🔧 Requirements

- Python 3.x
- Required libraries:
  - pandas  
  - numpy  
  - matplotlib  
  - scikit-learn  
  - minisom

You can install dependencies via pip.

### 📁 Dataset

The dataset used is the classic **Iris dataset**. It includes the following features:
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  
- Species (label)

### 📌 Project Workflow

1. Load the Iris dataset.
2. Drop the `species` column for unsupervised learning.
3. Standardize the feature data using `StandardScaler`.
4. Initialize and train a 10x10 SOM using `MiniSom`.
5. Map the original labels to the SOM nodes for visualization.
6. Visualize the SOM:
   - A pie chart grid representing class distributions across nodes.
   - A heatmap showing sample frequencies per SOM node.

### 📈 Output

- **Pie Chart Grid**: Displays how the different Iris species are clustered on the SOM grid.
- **Frequency Heatmap**: Highlights how many samples fall into each SOM node.

### 🧠 What is a SOM?

A Self-Organizing Map is an unsupervised neural network that projects high-dimensional data into a lower-dimensional (typically 2D) space, preserving topological properties of the input space.

### 🧾 License

This project is open source and free to use.

---