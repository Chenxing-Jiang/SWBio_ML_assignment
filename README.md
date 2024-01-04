# This README.md file describes what is in the repository

## ML assignment.ipynb file
- "ML assignment.ipynb" file is the notebook for the coding. Here is the description of the notebook:
We firstly import "zebrafish_TA_protein_prediction.xlsx" (I will call it "unknown protein dataset")and plot the datapoints based on the GRAVY (hydrophobicity) and tail charge. We want to know where those proteins in unknown protein dataset localize in the cell. 
- We then import "data_teacher_human.xlsx" file as a teacher dataset (I will call it "teacher dataset") to predict the localization of the proteins in the unknown protein dataset dataset. We use "KNeighborsClassifier" with teacher dataset to create a model that predict the localization of proteins in unknown protein dataset.
And finally we plot the dataset on a graph and obtain where the unknown proteins localize in the cells.


## "data_teacher_human.xlsx" file
"zebrafish_TA_protein_prediction.xlsx" file 
