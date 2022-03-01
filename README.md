 # Breast Cancer Detection
 
 
 Breast cancer is a disease in which cells in the breast grow out of control. There are different kinds of breast cancer. The kind of breast cancer depends on which cells in the 
 breast turn into cancer.

 Here we will use the "Breast Cancer Wisconsin (Diagnostic) DataSet". This dataset contains 569 patients with breast tumors. Several measurements and a diagnosis of malignant and 
 benign are available for each patient. The measurements will be used as features to make our predictions on the diagnosis.
 
 ## Goal of The Model
 
 The purpose of this Kernel is to develop a machine learning model that is capable of accurately predicting whether a tumor is benign or malignant, given several measurements. 
 For this purpose, first we will analyze this dataset and then and to try three diffenet deep learning classification models with and without early stopping and droupout layers
 and compare the obtained results.
 
 **Steps:**
 
 Importing and Exploring the data: Checking shape of the data,Checking any missing values, categorical values etc.
 Cleaning of Data, removing unnessary columns.
 Encoding of Data.
 Data Visualization: Coorelation of Featuers (using heatplot,pairplot)
 Spliting the Data into independent and dependent variables
 Feature scaling, so that features are on same scale.
 

**Making Model**

I have used 3 classifiers to train the model( logistic regreesion,Decision Tree and Random forest) as we can see that Decison Tree gave the best accuracy but during Testing 
Random forest gave the best accuracy, Random forest had LOW BIAS & LOW VARIANCE. Than i predicted the output using Random Forest classfier, the predicted values were having gud 
accuracy we can even notice that by ploating bargraph.
 
