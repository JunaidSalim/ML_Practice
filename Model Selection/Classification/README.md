# Classification Model Selection for Dry Bean Dataset

## Dataset Information

- **Data Set Name:** Dry Bean Dataset

**Abstract:**  
Images of 13,611 grains of 7 different registered dry beans were captured using a high-resolution camera. A total of 16 features were obtained from the grains, including 12 dimensions and 4 shape forms.

**Source:**  
Murat KOKLU  
Faculty of Technology, Selcuk University, Turkey.  
ORCID: 0000-0002-2737-2360  
Email: mkoklu@selcuk.edu.tr  
Ilker Ali OZKAN  
Faculty of Technology, Selcuk University, Turkey.  
ORCID: 0000-0002-5715-1040  
Email: ilkerozkan@selcuk.edu.tr

- **Data Type:** Multivariate
- **Task:** Classification
- **Attribute Type:** Categorical, Integer, Real
- **Area:** CS / Engineering
- **Format Type:** Matrix
- **Missing Values:** No
- **Number of Instances:** 13,611
- **Number of Attributes:** 17

**Relevant Information:**  
This research utilizes seven different types of dry beans, considering features such as form, shape, type, and structure based on market conditions. A computer vision system was developed to differentiate between these beans, resulting in 16 features extracted from 13,611 grain images using high-resolution cameras.

**Attribute Information:**  
1. Area (A)
2. Perimeter (P)
3. Major axis length (L)
4. Minor axis length (l)
5. Aspect ratio (K)
6. Eccentricity (Ec)
7. Convex area (C)
8. Equivalent diameter (Ed)
9. Extent (Ex)
10. Solidity (S)
11. Roundness (R)
12. Compactness (CO)
13. ShapeFactor1 (SF1)
14. ShapeFactor2 (SF2)
15. ShapeFactor3 (SF3)
16. ShapeFactor4 (SF4)
17. Class (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz, and Sira)

## Results

In selecting the best classification model for our dataset, all models were analyzed based on accuracy scores. The model with the highest accuracy, closest to one, was chosen as the best model.

The dataset used for model selection is `Data.csv`, which is already cleaned and numeric, requiring no preprocessing.

The accuracy scores of each classification model are as follows:

- **Logistic Regression:** 0.9256538348516016
- **Linear SVM:** 0.926829268292683
- **Kernel SVM:** 0.9318248604172789
- **KNN Classification:** 0.9244784014105202
- **Naive Bayes Classification:** 0.9003820158683514
- **Decision Tree Classification:** 0.9065530414340288
- **Random Forest Classification:** 0.9282985600940347

Therefore, based on the accuracy score, the **Kernel SVM Classification** model is considered the best for this dataset.

## Relevant Papers

KOKLU, M. and OZKAN, I.A., (2020), “Multiclass Classification of Dry Beans Using Computer Vision and Machine Learning Techniques.” Computers and Electronics in Agriculture, 174, 105507.  
DOI: [10.1016/j.compag.2020.105507](https://doi.org/10.1016/j.compag.2020.105507)

## Citation Requests / Acknowledgements

KOKLU, M. and OZKAN, I.A., (2020), “Multiclass Classification of Dry Beans Using Computer Vision and Machine Learning Techniques.” Computers and Electronics in Agriculture, 174, 105507.  
DOI: [10.1016/j.compag.2020.105507](https://doi.org/10.1016/j.compag.2020.105507)