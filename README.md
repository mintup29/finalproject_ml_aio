---

# **Forecasting IFI Trends per Aspect and per Cluster Using SARIMAX and XGBoost Machine Learning Methods**  
### **Case Study: Idea Box 2023-2024 Period**

## **Members**  
1. Aldi Cahyanugroho (2025)  
2. Rani Ridayani (3655)  
3. Vicko Danendra Setyo Yuwono (4530)  

---

## **Application Name**  
**FORECASTING IDEABOX**

---

## **Background**  
In order to improve the accuracy of budget calculations in the Kaizen Department, it is necessary to analyze IFI trends in the future.  

---

## **Purpose**  
Creating forecast data based on:  
1. **Aspect**: Quality, Cost, Safety, Energy, Environment, Work Efficiency (Process and Office areas), and Investment.  
2. **Clustering**: Date Created, Age, Aspect, and Department.  

This forecasting process is achieved using **SARIMAX** and **XGBoost** methods.

---

## **Result**  
After completing data preparation such as cleansing, merging, and determining data, the results obtained are as follows:  

### **Model Fit Evaluation**  
#### **Based on Aspect**  
- **RMSE Score on Test Set**: 59.57  
- **Mean Count**: 45.56227  
- **Standard Deviation (Std) Count**: 64.63560  

#### **Based on Clustering**  
- **RMSE Score on Test Set**: 47.51  
- **Mean Count**: 61.5  
- **Standard Deviation (Std) Count**: 59.8682  

These results indicate that the forecasting models achieve a **Good Fit** for predicting IFI trends.

---

## **Visualization**  
### **Example Results**
- Aspect-based forecasting trend visualization:
  ![Aspect Forecasting]([image1_placeholder](https://drive.google.com/uc?id=15e-KvQG_ioCCBZPMuLm5ckTJcwOZOqF-))
  ![Aspect2 Forecasting]([image2_placeholder](https://drive.google.com/uc?id=1wmeQN4mB5RKYMAnKs40fK6taAlH4W2kB))

- Clustering-based trend visualization:
  ![Clustering Forecasting]([image3_placeholder](https://drive.google.com/uc?id=1CoqF8aCDHfUrhMCe4nbsgoC0X19H8wEW))
  ![Clustering2 Forecasting]([image4_placeholder](https://drive.google.com/uc?id=1d68B4Mz01zcJDiivIX67QQ9g69o014oc))


---


## **Technologies Used**  
- **Python**  
- **SARIMAX** (Statsmodels)  
- **XGBoost**  
- **Data Visualization**: Matplotlib, Seaborn  
- **Jupyter Notebook** (for experimentation and prototyping)

---
