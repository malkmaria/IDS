# IDS Project Repository
**Topic - Lung Cancer Survival Prediction**  

**Authors - Maria Malk, Robert Israel, Hugo Martin Teemus**  

**Group - B5**  


## Motivation and goal
Lung cancer poses a significant health challenge globally, and survival rates hinge on various factors, especially the treatment path. 
This project focuses on predicting survival rates after the initial lung cancer diagnosis using synthetic medical data. 
Analyzing fictional patient treatment trajectories, our goal is to spot the key procedures, drugs, and differenttreatments that impact survival. 
Our aim is to develop a predictive tool toguide healthcare decisions for better patient care.

## Guide
**project_workflow.ipynb** - Contains the complete workflow of our project. Workflow consists of:  
- Loading and preprocessing the patient data
- Applying PCA for key feature identification
- Employing ML models, based on top scorers from initial testing:
  - RandomForest
  - SVM
  - KNeighbors
  - Gradient Boosting
- Evaluating the effectiveness of models by ROC-AUC scores
- Visualizing feature distributions in PCA space
- Conducting correlation analysis for further insights

**synthetic_data_lung_cancer.csv** - Synthetic training dataset containing treatment trajectories of lung cancer patients.
**synthetic_data_pca.csv** - Synthetic validation dataset containing treatment trajectories of prostate cancer patients.
