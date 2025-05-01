Gel Properties Analysis with Data Science

Overview

This project investigates how nanoscale and mesoscale protein structure influences the rheological behavior of food gels.  

Using synthetic data and a range of machine learning models — including multilinear regression, neural networks, and clustering — it simulates and predicts how structural parameters relate to mechanical performance.  

The project demonstrates how data science can help uncover structure–function relationships in food material science, particularly relevant to alternative proteins and precision-fermented dairy systems


Objectives

- Simulate structural and rheological data representing gel systems
- Analyze the impact of nanoscale and mesoscale features on gel rheology
- Build and compare models to predict mechanical properties
- Identify natural clusters of gels based on structure and behavior


Methods Used

| Technique                  | Purpose                                           |
|----------------------------|---------------------------------------------------|
| **Synthetic Data Generation** | Simulate protein gel structures and responses     |
| **Exploratory Data Analysis (EDA)** | Visualize distributions, correlations, and trends |
| **Multilinear Regression** | Model linear relationships between variables     |
| **Neural Networks**        | Capture nonlinear, complex structure–function mappings |
| **Clustering (e.g. K-Means)** | Group gels with similar properties               |
| **Model Evaluation**       | Compare accuracy using MAE, RMSE, R²              |


Technologies & Tools

- Python (Jupyter Notebook)
- `pandas`, `NumPy`, `matplotlib`, `seaborn`
- `scikit-learn` for regression, clustering
- `TensorFlow` / `Keras` or `PyTorch` for neural networks
- Feature engineering, scaling, and cross-validation methods


How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/IvorSpec/GelPropertiesProject.git

Launch the main notebook:
jupyter notebook "Project - gel properties.ipynb"


Future Work
Expand the synthetic dataset with greater noise and heterogeneity

Improve neural network architectures for predicting G’ and G’’

Compare simulated results to published literature on food gels and protein network formation

Explore feature transfer from real datasets in alt-protein or dairy research

Author
Ivor Spector
MSc Food Technology (Wageningen University & Research) | Food Scientist & Data Science Trainee

Collaborate or Connect
Have feedback, ideas, or relevant data to test?
I'm open to collaborations, informal R&D consulting, or PhD discussions.

Reach out via LinkedIn (https://www.linkedin.com/in/ivor-spector/) or GitHub.
