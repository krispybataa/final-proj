# COVID-19 Pediatric Data Analysis

This project analyzes a pediatric COVID-19 dataset using machine learning techniques to predict SARS-CoV-2 test results based on various clinical features.

## Models

The analysis includes:

1. **Logistic Regression Model**
   - Binary classification model predicting positive/negative SARS-CoV-2 test results
   - Features are preprocessed using:
     - Missing value imputation
     - Feature scaling
     - Handling of categorical variables

2. **Random Forest Classifier**
   - Ensemble learning method for classification
   - Provides feature importance ranking
   - Handles non-linear relationships in data
   - Includes:
     - Cross-validation
     - Confusion matrix analysis
     - Feature importance visualization

3. **K-Means Clustering**
   - Unsupervised learning approach to identify patterns
   - Optimal cluster selection using:
     - Elbow method
     - Silhouette analysis
   - Cluster analysis and comparison with actual labels
   - Visualization of cluster centers

4. **Principal Component Analysis (PCA)**
   - Dimensionality reduction technique to identify key patterns in the data
   - Preprocessing steps include:
     - Handling missing values using mean imputation
     - Removing features with >50% missing data
     - Feature standardization
   - Used to:
     - Reduce feature dimensionality
     - Identify important feature combinations
     - Visualize data patterns

## Dataset

The dataset contains various clinical features of pediatric patients, including:
- Patient demographics
- Laboratory test results
- Clinical conditions
- Hospital admission details

Target variable: SARS-CoV-2 exam result (positive/negative)

## How to Run

1. Install required python libraries:
   ```
   pandas
   numpy
   scikit-learn
   matplotlib
   seaborn
   ```

2. Open and run `.ipynb` files in Jupyter Notebook or JupyterLab:
   - The notebooks contain step-by-step analysis including:
     - Data preprocessing
     - Model training
     - Performance evaluation
     - Visualization of results

3. The notebooks will guide you through:
   - Loading and cleaning the dataset
   - Feature preprocessing and selection
   - Model training and evaluation
   - Results interpretation

## Results

The analysis provides insights into:
- Important clinical features for COVID-19 prediction in pediatric patients
- Model performance metrics and comparison
- Feature importance analysis from Random Forest
- Cluster patterns from K-Means analysis
- Dimensionality reduction and data patterns through PCA