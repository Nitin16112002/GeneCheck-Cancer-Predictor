# **Gene-Based Cancer Prediction Using KNN**

## **Overview**
This project applies the K-Nearest Neighbors (KNN) algorithm to predict cancer presence based on two genetic markers. The model demonstrates high accuracy and reliability in distinguishing between cancerous and non-cancerous cases.

## **Dataset**
- **Total Samples:** 3,000  
- **Features:**  
  - `Gene One` (Float)  
  - `Gene Two` (Float)  
- **Target Variable:** `Cancer Present` (Binary: 1 = Yes, 0 = No)  


## **Model Performance**
### **Training & Testing Accuracy**
- **Train Accuracy:** 94.08%  
- **Test Accuracy:** 93.17%  
- **Cross-Validation Score:** 94.00%  

### **Confusion Matrix**

- **True Positives:** 293  
- **True Negatives:** 266  
- **False Positives:** 17  
- **False Negatives:** 24  

### **Classification Report**
| Metric       | Class 0 (No Cancer) | Class 1 (Cancer) | Overall |
|-------------|--------------------|----------------|---------|
| **Precision** | 92%                | 95%            | 93%     |
| **Recall**    | 94%                | 92%            | 93%     |
| **F1-score**  | 93%                | 93%            | 93%     |
| **Accuracy**  | -                  | -              | 93%     |



## **Conclusion**  
The KNN model successfully predicts cancer presence using genetic markers, achieving a **93% accuracy**. The results indicate a strong potential for **gene-based cancer diagnostics** with minimal false predictions.  
