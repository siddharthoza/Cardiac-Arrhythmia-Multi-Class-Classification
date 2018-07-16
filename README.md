# Machine-Learning  

Cardiac Arrhythmia Multy-Class Classification

## Abstract: 
This study is conducted to classify patients into one of the sixteen subclasses, among which one class represents absence of disease and the other fifteen classes represent electrocardiogram records of various subtypes of arrhythmias.

## Goal: 
As it is a huge dataset with nearly 280 variables first I performed feature selection technique to identify the important variable. Then I applied simple machine learning models like KNN, logistic regression, random forest, decision tree, linear & kernalised SVM and compared the precision and recall of each of the above mentioned models. After running the simple models I wanted to see how these models perform after bagging and boosting. As the data file had 280 variables, PCA looked as the best option.Hence after performing PCA on the above models we got the best model with accuracy as 75%. 

## Source:
The dataset was created by Angeliki Xifara and was processed by Athanasios Tsanas, Oxford Centre for Industrial and Applied Mathematics, University of Oxford, UK).

## Data Set Information:
We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.

## Attribute Information:
The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses. 

## Specifically: 
-	X1	Relative Compactness 
-	X2	Surface Area 
-	X3	Wall Area 
-	X4	Roof Area 
-	X5	Overall Height 
-	X6	Orientation 
-	X7	Glazing Area 
-	X8	Glazing Area Distribution 
-	y1	Heating Load 
-	y2	Cooling Load


