# Predicting-Cancer-using-Random-Forest
- Predicting type of cell, whether it is benign or malignant and explain the prediction using SHAP.
- The dataset can be loaded using this link: https://raw.githubusercontent.com/dphi-official/Datasets/master/breast_cancer/Training_set_breastcancer.csv
- The predictive model used is Random Forest with minor estimator tweak which give an accuracy of 96%.
- Using SHAP to create force plot to visualize how does the model make prediction.
- Created summary plot to identify the most importance variables
- Created dependency plot to visualize the dependecy of 2 variables in making prediction.
- Some of the plot cannot be viewed in Github, download the notebook to view it.

## About the dataset

Different features related to the breast are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe the characteristics of the cell nuclei present in the image.

- id: Id number
- dagnosis: Cancer is Malignant or Benign (M = malignant, B = benign) - target variable

Other 20 features contain information about following 10 real valued features

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)
