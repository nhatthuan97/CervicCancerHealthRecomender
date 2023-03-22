# CervicCancerHealthRecomender
The goal of this note book is to replicate the research done by the paper with the same name 
Overall some notes in implemenatation:
- SMOTE has to be used to balance the training data set
- Used different machines learning models for this dataset
  - Current implemenation only have catboost
- Biopsy is used as the target class
- Use MOGA(Multi-Objective Genetic Algorithm to narrow down the feature sets --- Later) 

Cited paper:
Kuanr, Madhusree, et al. “Health Recommender System for Cervical Cancer Prognosis in Women.” 2021 6th International Conference on Inventive Computation Technologies (ICICT), Inventive Computation Technologies (ICICT), 2021 6th International Conference On, Jan. 2021, pp. 673–79. EBSCOhost, https://doi-org.ezproxy.mtsu.edu/10.1109/ICICT50816.2021.9358540.

#Navigation of the folder
- Reading sources: all pdf of the paper that is used. The notes for these pdf are inside a powerpoint fiel "Reading Report.pptx"
- Data: location of the data used for training and testing
- catboost_info: part of the catboos import
