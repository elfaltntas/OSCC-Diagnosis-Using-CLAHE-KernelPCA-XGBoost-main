# 🚀 OSCC Diagnosis Project

🚀 *Implementation of image processing and classification methods for the diagnosis of Oral Squamous Cell Carcinoma (OSCC)*

This project examines data processing methods used in OSCC diagnosis and the performance of the XGBoost algorithm. By combining CLAHE and Kernel PCA methods, an accuracy rate of 98% was achieved.

---

## 🎯 Project Summary

- *Objective:* To identify the most effective classification algorithm and data processing techniques for OSCC diagnosis.  
- *Methods:*  
  - CLAHE (Contrast Limited Adaptive Histogram Equalization)  
  - Kernel PCA (Principal Component Analysis)  
  - XGBoost algorithm  
- *Results:* The combination of CLAHE and Kernel PCA achieved the highest performance with a 98% accuracy rate.  

---

## 📚 Literature Summary

- *OSCC:* The most common type of oral cancer. When not diagnosed early, it leads to high mortality rates.  
- *Traditional Methods:*  
  - Support Vector Machines (SVM): 85% accuracy rate.  
  - Deep Learning Models (Xception): 92% accuracy rate.  
- *This Study:* The integration of CLAHE and Kernel PCA methods with XGBoost provides a significant contribution to the literature with a 98% accuracy rate.  

---

## ⚙ Materials and Methods

### 1. Dataset Used
- A dataset labeled for OSCC diagnosis obtained from Kaggle.  

### 2. Applied Methods
- *CLAHE:* A method that enhances image contrast and emphasizes details.  
- *Kernel PCA:* A nonlinear method used in dimensionality reduction and data analysis.  
- *CLAHE + Kernel PCA:* The combination of the two methods improved classification performance.  

### 3. Classification
- *Algorithm:* XGBoost  
- *Evaluation Metrics:*  
  - Accuracy  
  - MCC (Matthews Correlation Coefficient)  
  - Precision  
  - Recall  

---

## 📊 Findings and Discussion

- *Raw Data:* 83% accuracy rate.  
- *CLAHE:* Limited improvement when used alone (74% accuracy rate).  
- *Kernel PCA:* 94% accuracy rate, a significant improvement.  
- *CLAHE + Kernel PCA:* 98% accuracy rate, the best result.  

### 📈 Charts:
- When CLAHE and Kernel PCA are applied together, contrast and principal component analysis are successfully enhanced.  

---

## 🧑‍🔬 Conclusion and Recommendations

- The combination of CLAHE and Kernel PCA achieved high accuracy in OSCC diagnosis.  
- *Recommendations:*  
  - The study should be tested on different medical image datasets.  
  - Generalizability analyses can be conducted with larger datasets.  
  - These methods can be combined with deep learning algorithms.  

---

## 🔗 References

1. [Liu, Y., Shen, D., & Jiang, Z.](https://www.researchgate.net/publication/384887553)  
2. [Abdelrahman, H. A., et al.](https://www.researchgate.net/publication/347094899)  
3. [Nunes, F. H., et al.](https://doi.org/10.1016/j.radi.2021.174)  
4. [Scholkopf, B., Smola, A. J., & Muller, K. R.](https://doi.org/10.1162/089976698300017467)  
5. [Kaggle Dataset](https://www.kaggle.com)  

The dataset was taken from here:  
https://data.mendeley.com/datasets/ftmp4cvtmb/2


## 📞 Contact

For any questions or collaborations:

- 📧 elfaltntas123@gmail.com
