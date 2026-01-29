#  Breast Cancer Classification using Machine Learning

This project demonstrates a complete machine learning workflow for predicting whether a tumor is **malignant or benign** using the Breast Cancer dataset provided by **scikit-learn**.

The project covers:
- Data loading
- Exploratory Data Analysis (EDA)
- Feature inspection
- Model training
- Performance evaluation

All steps are implemented inside the Jupyter Notebook: `training.ipynb`.

---

##  Dataset

- Source: `sklearn.datasets.load_breast_cancer()`
- Samples: 569
- Features: 30 numerical features computed from digitized images of breast mass
- Target:
  - `0` → Malignant
  - `1` → Benign

The dataset is converted into a Pandas DataFrame for easier analysis and processing.

---

##  Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn


---

##  Exploratory Data Analysis (EDA)

The following analyses are performed:

- Dataset shape and structure
- Feature data types
- Missing value detection
- Statistical summary of features
- Target class distribution

This helps understand:
- Data quality
- Feature ranges
- Class balance

---


##  How to Run the Project

### Option 1: Using Jupyter Notebook (Local)

1. Clone or download the repository
2. Install required packages:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter

3. Open the notebook:

    ```bash
    jupyter notebook training.ipynb


4. Run all cells from top to bottom

---
### Option 2: Using Google Colab

1. Upload training.ipynb to Google Colab

2. Run each cell sequentially

3. No dataset upload needed (dataset loads from sklearn)
