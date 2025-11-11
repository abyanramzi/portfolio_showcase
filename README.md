# 👋 Hi, I'm Abyan Ramzi
**Machine Learning & IoT Developer**  
Building intelligent systems that connect things, data, and automation.  
---

## 👤 About Me
I’m a technology enthusiast passionate about **Machine Learning & IoT**.  
My focus is bridging **research and real-world implementation** — turning ideas into functional, data-driven systems.

- 🎓 Background: Telecommunication 
- 💼 Experience: Computer Vision & IoT
- 💼 Looking for: R&D / AI Engineer / Data-Centric roles
- 📫 Contact: [LinkedIn](https://linkedin.com/in/abyanramzi) | [Email](abyanramzi.ta@gmail.com)

---

## 🧠 Machine Learning & Computer Vision Projects

### 🔹 [DETECTRON2 + SORT Tracking for Retail Product Counting](https://github.com/abyanramzi/detectron2-retail-product-counting.git)
It was developed as part of a **research and development initiative** to improve an existing client solution where **hand movements were mistakenly counted** as product transitions.
Two main results were achieved:

1. ✅ **Accurate counting** of retail products moving across the line.  
2. 🚫 **No false detection** for hand movements near the line.

| Scenario | Example GIF |
|-----------|--------------|
| Product Counting | ![Counting Example](https://raw.githubusercontent.com/abyanramzi/detectron2-retail-product-counting/master/assets/product_counting.gif) |
| Hand Exclusion | ![Hand Filtering Example](https://raw.githubusercontent.com/abyanramzi/detectron2-retail-product-counting/master/assets/hand_exclusion.gif) |

#### ⚙️ About System

Detectron 2 | OpenCV | Kalman Filter | Hungarian Algorithm | Counthing Logic

### 🔹 [YOLOv7 + Thermal and RGB Camera for Poultry Counting and Classification](https://github.com/abyanramzi/yolov7-thermal-rgb-bird-detection.git)
This research focusing on **number of birds** and their **species identification**. We adopt **YOLOv7**, that integrated to two types of cameras:
- **RGB Camera** — captures standard visual images.
- **Thermal Camera** — provides infrared imaging for detection in challenging lighting conditions.  
We introduce a **cage contour measurement technique**, which classifies cages based on the percentage of obstacles (from least to most obstructed). The performance of the detection model is then compared across both camera types under varying cage conditions.  
The two prediction results below illustrate different conditions captured by the RGB and Thermal cameras.  
- **RGB Prediction**: Actual condition includes 4 quails, 1 pigeon, and 5 lovebirds.  
- **Thermal Prediction**: Actual condition includes 8 quails.  

| RGB Prediction | Thermal Prediction |
|----------------|-------------------|
| <img src="https://raw.githubusercontent.com/abyanramzi/yolov7-thermal-rgb-bird-detection/master/results/predict_result_example/output_rgb.jpg" width="320"> | <img src="https://raw.githubusercontent.com/abyanramzi/yolov7-thermal-rgb-bird-detection/master/results/predict_result_example/output_thermal.jpg" width="320"> |

#### ⚙️ About System

YOLOv7 | OpenCV | Streamlit | Thermal and RGB Camera | Instance Segmentation

---

## 📊 Data Analysis Projects

### 🔹 [Bank Transaction Fraud Detection Using K-Means Clustering](https://github.com/abyanramzi/bank-transaction-fraud-detection.git)
The study case focuses on how transaction frequency, amount, and behavioral signals (such as login attempts) can indicate unusual or high-risk activity. My aims to **detect potential fraudulent banking transactions** by analyzing customer behavioral patterns using **unsupervised learning (K-Means Clustering)**

#### 🖥️ Preview

| **Description** | **Preview** |
|------------------|-------------|
| Correlation Matrix | <img src="https://raw.githubusercontent.com/abyanramzi/bank-transaction-fraud-detection/master/assets/eda_correlation.png" width="640"/> |
| Behavior Scatter | <img src="https://raw.githubusercontent.com/abyanramzi/bank-transaction-fraud-detection/master/assets/eda_scatter.png" width="640"/> |
| K-Elbow Curve | <img src="https://raw.githubusercontent.com/abyanramzi/bank-transaction-fraud-detection/master/assets/elbow_curve.png" width="640"/> |
| PCA Clusters | <img src="https://raw.githubusercontent.com/abyanramzi/bank-transaction-fraud-detection/master/assets/pca_clusters.png" width="640"/> |


#### ⚙️ About System

Machine Learning | KMeans Clustering | Data Visualization | Data Analysis

### 🔹 [Game Data Analysis for Business Improvement](https://github.com/abyanramzi/game-data-analysis.git)
Coming Soon

#### ⚙️ About System
ETL | PostgreSQL | Data Visualization | Data Analysis

---

## 🧩 Research & Purposed Concepts

### 🔹 [Quameaty: Application for Meat Quality Detection](https://dx.doi.org/10.31544/jtera.v7.i1.2022.107-114)
The purpose of this study is to create a tool that is useful in detecting the quality of raw chicken meat by utilizing image processing using the InceptionV3 model and named Quameaty. 

#### 🖥️ Preview

| **Home** | **Detection Result** | **History** |
|-----------|----------------------|--------------|
| <img src="assets/quameaty/home_page.png" width="320"/> | <img src="assets/quameaty/detection_result.png" width="320"/> | <img src="assets/quameaty/history.png" width="320"/> |


#### ⚙️ About System

Tensorflow Lite | InceptionV3 | Fluter | Image Classification 

### 🔹 [PoxDaig: Application for Monkeypox Diagnosis](https://docs.google.com/presentation/d/161wSFoGKiW1TZ9xEfcEptZWjfWO7Nheu/edit?usp=sharing&ouid=113243255286445203185&rtpof=true&sd=true)
In 2022, global monkeypox cases increased again, reaching **3,413 cases** across **50 countries**, including Indonesia.  
We proposed this application for monkeypox diagnosis in the **National Scientific Writing Competition** at **Universitas Muhammadiyah Surakarta**.  
Our proposed solution **won the competition**.

#### 🖥️ Preview

| **Home** | **Detection Result** | **History** |
|-----------|----------------------|--------------|
| <img src="assets/poxdiag/home_page.png" width="320"/> | <img src="assets/poxdiag/detection_result.png" width="320"/> | <img src="assets/poxdiag/history.png" width="320"/> |

  
#### ⚙️ About System

Tensorflow Lite | InceptionV3 | Kotlin | Image Classification 

---


> _This repository serves as a showcase of my projects, research, and ideas across AI, Data, and IoT fields._
