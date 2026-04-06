# PCA and Clustering Analysis of Wildfire Risk in São Paulo (Brazil)

This repository contains a Python-based pipeline for data preprocessing, dimensionality reduction using Principal Component Analysis (PCA), and clustering analysis applied to wildfire-related indicators across municipalities in São Paulo, Brazil.

The workflow is designed to support exploratory data analysis and territorial classification based on environmental, climatic, and socioeconomic variables.

---

## 📂 Repository Structure

```
data/
├── raw/          # Raw data (not included)
├── processed/    # Cleaned datasets (not included)
├── features/     # Feature-engineered datasets (not included)
├── aux/          # Auxiliary data (e.g., coordinates)

notebooks/
├── script_for_pca_organizado.ipynb
└── script_for_cluster_organizado.ipynb

outputs/          # Results, figures, and exports (not included)
models/           # Saved models (if applicable)
```

---

## ⚠️ Data Availability

The datasets used in this project are **not publicly available** at this stage due to ongoing research and publication processes.

To run the notebooks, users must provide their own datasets and place them in the appropriate directories inside the `data/` folder.

---

## 🔬 Methodological Workflow

The analysis follows these main steps:

1. **Data preprocessing**

   * Cleaning and standardization of variables
   * Aggregation and transformation of municipal-level data

2. **Feature engineering**

   * Construction of derived variables (e.g., mean, variability, trends)

3. **Dimensionality reduction**

   * Application of PCA to reduce multicollinearity and dimensionality

4. **Clustering analysis**

   * K-Means clustering for identifying territorial patterns
   * Evaluation of cluster structure using validation metrics

5. **Interpretation**

   * Characterization of clusters
   * Spatial and analytical interpretation of wildfire-related patterns

---

## 🧪 Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/pca-clustering-wildfires-sp.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Add your datasets to the `data/` directory following the expected structure.

4. Open the notebooks:

* `script_for_pca_organizado.ipynb`
* `script_for_cluster_organizado.ipynb`

---

## 📌 Notes

* The repository focuses on methodological reproducibility.
* Data privacy and publication constraints are respected.
* The structure is designed for scalability and future integration of additional analyses.

---

## 📬 Contact

For questions, collaboration, or data access requests, please get in touch.
