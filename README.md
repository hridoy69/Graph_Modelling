# Probing into Graph-based Models for Predicting Active Compounds against Triple Negative Breast Cancer
In this study, we curated a dataset of 756 mutant-type compounds from three cell lines and developed four graph-based models to predict active compounds against TNBC. Validated using 10-fold cross validation and optimized with the Optuna framework, the models achieved predictive accuracy with AUC values of 0.65 – 0.83, with the MPNN model outperforming all the others. Furthermore, key structural fragments associated with cell inhibition and model predictions were identified and interpreted using several explainability techniques. Validation with an external set of FDA-approved drugs demonstrated prediction accuracies ranging from 66% to 97%, highlighting the robustness of the models in identifying compounds with potential inhibitory activity against TNBC cells. 

# Guidelines
Users can follow the following guidelines for reproducing the models - 
1. The users need to make an environment with the required Python libraries as mentioned in 'requirements.txt'.
2. All the Python codes or models can be run in Jupyter notebook.
3. A folder can be prepared with these model codes and datasets - 'dataset_main.xlsx', which is the primary dataset of 756 smiles and targets
4. Separately, two external sets 'Phytos-results.xlsx' and 'cancer-fda.xlsx' are used for external validation.
5. Each Python file like  
