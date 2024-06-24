DeepCIM_main / 
Our main model and the entire workflow. This repository contains the code and resources for DeepCIM project which predicts chemotherapy-induced myelosuppression (CIM) based on binding interactions between chemotherapeutic molecules and proteins. The first part includes data preparation, preprocessing and summary of data in different plots. Second part consists of model architecture, training and evaluation. Davis test set -> External validation dataset / BindingDB test set -> Internal test dataset.
![image](https://github.com/tlee23-ic/AZ-project-2023-2024/assets/151794938/166f86a5-8857-4fa3-9e49-85977eba600b)

![image](https://github.com/tlee23-ic/AZ-project-2023-2024/assets/151794938/874c7c16-1f15-4d9b-bf6b-1043d08f8e3c)


AZ_Dataset_CDDD_experiments / 
This repository contains codes for extracting, analysing and validating data from the DrugBank database. I used the method developed by Dhimmel to extract and process XML data downloaded from the DrugBank. CDDD (Continuous and Data-Driven Descriptors, https://github.com/jrwnter/cddd) is a model developed by Winter et al, that encodes SMILES string to a 512 latent vector and also capable of decodes back to the SMILES string with high reconstruction rate (93.106% for DrugBank molecules).
AZ_Dimension_reduction / 
This repository contains workflow for dimensionality reduction and provide visualisation of chemical space (myelosuppressive / non-myelosuppressive). ECFP4 fingerprint was used to transform molecular structures to machine readable vector format. PCA and UMAP were employed as dimensionality reduction methods.
