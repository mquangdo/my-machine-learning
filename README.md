# 🤖 My Machine Learning

A personal collection of Jupyter notebooks exploring and implementing core Machine Learning algorithms, techniques, and real-world projects — built for learning and reference.

---

## 📚 Contents

### Supervised Learning

| Topic | Directory | Description |
|-------|-----------|-------------|
| Linear Regression | [`LinearRegression/`](LinearRegression/) | Linear regression fundamentals and testing |
| Logistic Regression | [`LogisticRegression/`](LogisticRegression/) | Binary and multiclass classification |
| Decision Tree | [`DecisionTree/`](DecisionTree/) | Decision tree implementation and visualization |
| K-Nearest Neighbors | [`K-Nearest-Neighbors/`](K-Nearest-Neighbors/) | KNN algorithm from scratch and with scikit-learn |
| Support Vector Machine | [`Support Vectors Machine/`](Support%20Vectors%20Machine/) | SVM for classification and regression |
| Regularization | [`Regression/`](Regression/) | Ridge (L2) and Lasso (L1) regression |
| Gradient Descent | [`GradientDescent/`](GradientDescent/) | Gradient descent optimization algorithm |
| Ensemble Learning | [`EnsembleLearning/`](EnsembleLearning/) | Stacking and ensemble methods |
| Imbalanced Data | [`ImbalancedData/`](ImbalancedData/) | Confusion matrix, precision, recall for imbalanced datasets |

### Unsupervised Learning

| Topic | Directory | Description |
|-------|-----------|-------------|
| K-Means Clustering | [`K-MeansClustering/`](K-MeansClustering/) | K-means, elbow method, image segmentation |
| DBSCAN | [`Clustering/DBSCAN/`](Clustering/DBSCAN/) | Density-based spatial clustering |
| Dimensionality Reduction | [`DimensionalityReduction/`](DimensionalityReduction/) | PCA, LDA, t-SNE, Isomap |

### Projects

| Project | Directory | Description |
|---------|-----------|-------------|
| California Housing Prices | [`Project/AurelienGeron/`](Project/AurelienGeron/) | End-to-end regression pipeline (from *Hands-On ML*) |
| MNIST Classification | [`Project/AurelienGeron/`](Project/AurelienGeron/) | Multi-class classification on the MNIST dataset |
| Titanic Survival | [`Project/TitanicDataset/`](Project/TitanicDataset/) | Kaggle Titanic competition — survival prediction |
| Spam Mail Detection | [`Project/SpamMailDetection/`](Project/SpamMailDetection/) | Email spam classifier using logistic regression |
| Stock Market Analysis | [`Test/`](Test/) | Preparing and analyzing 5-year stock market data |

### Tutorials & Course Notes

| Source | Directory | Description |
|--------|-----------|-------------|
| Hands-On ML (Aurélien Géron) | [`hands_on_ml/`](hands_on_ml/) | Notebooks for Chapters 2 & 5 |
| DataScienceWorld-Khan | [`DataScienceWorld-Khan/`](DataScienceWorld-Khan/) | Chapter-by-chapter course notebooks (Chap1–9) |
| scikit-learn Tutorials | [`Tutorial/`](Tutorial/) | Preprocessing, metrics, and feature engineering |

---

## 🛠️ Tech Stack

- **Python 3**
- [scikit-learn](https://scikit-learn.org/) — ML algorithms and pipelines
- [pandas](https://pandas.pydata.org/) — Data manipulation
- [NumPy](https://numpy.org/) — Numerical computing
- [Matplotlib](https://matplotlib.org/) — Data visualization
- [TensorFlow / Keras](https://www.tensorflow.org/) — Deep learning (selected notebooks)
- [Jupyter Notebook](https://jupyter.org/) — Interactive notebook environment

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/mquangdo/my-machine-learning.git
   cd my-machine-learning
   ```

2. **Install dependencies**
   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. Navigate to any topic directory and open the `.ipynb` notebook to get started.

---

## 📁 Repository Structure

```
my-machine-learning/
├── Clustering/              # DBSCAN
├── DataScienceWorld-Khan/   # Course notes (Chap1–9)
├── DecisionTree/
├── DimensionalityReduction/ # PCA, LDA, t-SNE, Isomap
├── EnsembleLearning/        # Stacking
├── GradientDescent/
├── ImbalancedData/          # Evaluation metrics
├── K-MeansClustering/
├── K-Nearest-Neighbors/
├── LinearRegression/
├── LogisticRegression/
├── Project/                 # Real-world projects
│   ├── AurelienGeron/
│   ├── Dataflow/
│   ├── HomeworkSIC/
│   ├── SpamMailDetection/
│   └── TitanicDataset/
├── Regression/              # Ridge & Lasso
├── Support Vectors Machine/
├── Test/                    # Stock market analysis
├── Tutorial/                # sklearn preprocessing & metrics
└── hands_on_ml/             # Hands-On ML book notebooks
```

---

## 📖 References

- [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) — Aurélien Géron
- [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
