# This README.md file describes what is in the repository

## ML assignment.ipynb file
- We firstly import "zebrafish_TA_protein_prediction.xlsx" (I will call it "unknown protein dataset")and plot the datapoints based on the GRAVY (hydrophobicity) and tail charge. We want to know where those proteins in unknown protein dataset localize in the cell. 
- We then import "data_teacher_human.xlsx" file as a teacher dataset (I will call it "teacher dataset") to predict the localization of the proteins in the unknown protein dataset dataset. We use "KNeighborsClassifier" with teacher dataset to create a model that predict the localization of proteins in unknown protein dataset.
And finally we plot the dataset on a graph and obtain where the unknown proteins localize in the cells.

## "data_teacher_human.xlsx" file
- This is a dataset of proteins whose subcellular information have alreday been reported before. The file contains the name of the proteins, subcellular location of proteins, isoforms etc. We only use "name", "TMD", "GRAVY" and "Tail charge".

  
## "zebrafish_TA_protein_prediction.xlsx" file
- This is a dataset that contains about 1000 of proteins that are predicted as tail-anchored proteins, but their subcellular localization are not clear. The file contains multiple information of each protein as in "data_teacher_human.xlsx" file, but we only used "Annotated as", "TMD", "GRAVY" and "Tail charge" information (*"Annotated as" indicates protein's name). 
