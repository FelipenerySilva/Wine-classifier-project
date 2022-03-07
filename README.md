# Linear and Quadratic Discriminant Analysis, KNN and Naive Bayes - Wine classifier
 
We are interested in developing a tool that can classify wines into one of the three types based
on the other variables provided.

The data set wine.csv contains quality information about a number of wines of different types.
The vintage variable indicates the wine type using codes A, B and C. The colour variable is
categorical information coded as col1 to col4. All other variables are concentrations of different
substances but are not all reported on the same scale.

In this project I have: 
Performed cross-validated LDA (LOOCV) with variable vintage as the response,
and all the numeric variables as predictors. Computed and display the confusion matrix as well as the 
corresponding classification accuracy and error.

Performed cross-validated QDA (LOOCV) and compared the LOOCVresults with those obtained by LDA.

Performed cross-validated KNN (LOOCV) with variable vintage as the response,
and all the numeric variables as predictors. Used a loop to compute the (cross-validated)
classification accuracy and error for k between 1 and 15.

Performed cross-validated Naive Bayes (LOOCV) with variable vintage as the response, 
and all the numeric variables as predictors. Implemented the LOOCV using my own code to loop 
through the data leaving out one observation at a time. Compared my predictions to actual classes 
for vintage using a confusion matrix and calculated classification error and accuracy.

This project was part of the Predictive Analytics course from the University of Newcastle (Uon) 
Master of Data Science Degree.

I have used R Studio to prepare a final R Markdown document.


