## ML assignment.ipynb file
- This is a notebook of the coding that I conducted.
- We firstly import "zebrafish_TA_protein_prediction.xlsx" (I will call it "unknown protein dataset")and plot the datapoints based on the GRAVY (hydrophobicity) and tail charge. We want to know where those proteins in unknown protein dataset localize in the cell. 
- We then import "data_teacher_human.xlsx" file as a teacher dataset (I will call it "teacher dataset") to predict the localization of the proteins in the unknown protein dataset dataset. We use "KNeighborsClassifier" with teacher dataset to create a model that predict the localization of proteins in unknown protein dataset.
And finally we plot the dataset on a graph and obtain where the unknown proteins localize in the cells.

## "data_teacher_human.xlsx" file
- This is a dataset of proteins whose subcellular information have alreday been reported before. The file contains the name of the proteins, subcellular location of proteins, isoforms etc. We only use "name", "TMD", "GRAVY" and "Tail charge".
- The data is obtained from Costello et al., JCS, 2017 (https://journals.biologists.com/jcs/article/130/9/1675/56732/Predicting-the-targeting-of-tail-anchored-proteins).
- "data_teacher_human.xlsx" should be included in the location as script.py.

  
## "zebrafish_TA_protein_prediction.xlsx" file
- From data protection prespective, this file is uploaded via Blackboard. 
- This is a dataset that contains about 1000 of proteins that are predicted as tail-anchored proteins, but their subcellular localization are not clear. The file contains multiple information of each protein as in "data_teacher_human.xlsx" file, but we only used "Annotated as", "TMD", "GRAVY" and "Tail charge" information (*"Annotated as" indicates protein's name).
-  "zebrafish_TA_protein_prediction.xlsx" file should be included in the location as script.py. 
