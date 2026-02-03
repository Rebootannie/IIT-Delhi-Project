Chronic Pain Classification using MVPA and Explainable AI
This repository implements a robust machine learning pipeline to classify chronic musculoskeletal pain using Multivariate Pattern Analysis (MVPA) on fMRI data. The project integrates neurologic biomarker discovery with Explainable AI (XAI) to provide interpretable clinical insights.

📌 Project Overview
Chronic pain often lacks clear structural abnormalities in conventional imaging. This project uses functional MRI (fMRI) to capture distributed neural activity patterns associated with sustained pain states. By extracting mean activation from brain regions defined by the AAL atlas, we employ various classifiers to achieve high diagnostic accuracy.

🚀 Key Features

Data Standard: Uses open-source BIDS-compliant datasets (ds000208 for chronic pain and ds000140 for acute pain).


Advanced Modeling: Implements Random Forest, SVM, and LDA classifiers.


Dimensionality Reduction: Utilizes PCA and t-SNE to explore separability between pain and control groups.


Explainability: Integrates SHAP and LIME to interpret model predictions and reveal neurobiological insights.


Performance: The Random Forest model achieves 95% accuracy with high interpretability.

🛠️ Tech Stack
Language: Python

Neuroimaging: nilearn, nibabel

Machine Learning: scikit-learn

Exploration: matplotlib, numpy, pandas


XAI: SHAP, LIME 

📂 Repository Structure

IIT_DELHI.pdf: Full research paper detailing the methodology and neurologic pain signatures.

IIT_Delhi_Project.ipynb: Jupyter Notebook containing the end-to-end implementation from data unzipping to model interpretation.

📊 Results & Insights
The analysis identifies specific brain regions—such as the Cerebellum, Olfactory, and Hippocampus—as significant features for pain classification. Dimensionality reduction via PCA helps visualize the clear separation between groups, enabling objective pain assessment.

🎓 Acknowledgments
Developed at IIT Delhi and IIT Patna by Ananya Maldyar, Shobha Sharma, and Tapan K. Gandhi. Special thanks to OpenNeuro contributors for the datasets.
