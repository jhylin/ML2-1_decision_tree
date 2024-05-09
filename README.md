#### **Machine learning series 2.1 - Decision tree**

Machine learning (ML) series 2 will be largely about tree models, which encompass decision tree, random forest, XGBoost and LightGBM. I'm planning to have deeper dives into using each of these tree models on drug discovery data from ChEMBL database (as allowed by my current hardware set-ups). I'll also attempt to save different tree models in different repositories as I work on them later.

This repository will hold most of the data and files used in ML series 2.1 for building a decision tree model. All the code used here was run in Python 3.9 venv and available in .ipynb or .qmd files depending on the preferences.

This series was presented as 3 posts with links provided below:

[Post 1](https://jhylin.github.io/Data_in_life_blog/posts/16_ML2-1_Decision_tree/1_data_col_prep.html) - data collection from ChEMBL database using web resource client in Python, with initial data preprocessing

[Post 2](https://jhylin.github.io/Data_in_life_blog/posts/16_ML2-1_Decision_tree/2_data_prep_tran.html) - more data preprocessing and transformation to reach the final dataset prior to model building

[Post 3](https://jhylin.github.io/Data_in_life_blog/posts/16_ML2-1_Decision_tree/3_model_build.html) - estimating experimental errors and building decision tree model using scikit-learn

Other way to access above posts is directly through my [blog](https://jhylin.github.io/Data_in_life_blog/).

---

#### **ML series 1 - Logistic regression**

Rather than placing all the work done for ML series 1 in another repository, I thought I'll leave them below as links (since they were done a while back with a large .csv file downloaded via ChEMBL webpage that I could not fit onto the free GitHub repository, this problem is likely avoided in series 2 when using the ChEMBL web resource client).

Posts: 
* [ML1.1 - data preparation](https://jhylin.github.io/Data_in_life_blog/posts/08_ML1-1_Small_molecules_in_ChEMBL_database/ML1-1_chembl_cpds.html)
* [ML1.2 - cross-validation and hyperparameter tuning](https://jhylin.github.io/Data_in_life_blog/posts/10_ML1-2_Small_molecules_in_ChEMBL_database/ML1-2_chembl_cpds.html)
* [ML1.3 - re-training and re-evaluating model](https://jhylin.github.io/Data_in_life_blog/posts/11_ML1-3_Small_molecules_in_ChEMBL_database/ML1-3_chembl_cpds.html)

Code: 
* [ML1.1 - data preparation](https://github.com/jhylin/Data_in_life_blog/blob/main/posts/08_ML1-1_Small_molecules_in_ChEMBL_database/ML1-1_chembl_cpds.qmd) 
* [ML1.2 - cross-validation and hyperparameter tuning](https://github.com/jhylin/Data_in_life_blog/blob/main/posts/10_ML1-2_Small_molecules_in_ChEMBL_database/ML1-2_chembl_cpds.qmd)
* [ML1.3 - re-training and re-evaluating model](https://github.com/jhylin/Data_in_life_blog/blob/main/posts/11_ML1-3_Small_molecules_in_ChEMBL_database/ML1-3_chembl_cpds.qmd)
