# 📱 Product Price Prediction

## 1️⃣ Project Overview 📌

This project predicts the **price range of mobile phones** based on their hardware features and specifications.  
Using **Python** and **Machine Learning algorithms**, models are trained to classify mobile phones into **four price categories** — from low to very high — based on attributes such as RAM, battery power, and display resolution.  

The project demonstrates **data analysis**, **model building**, and **performance comparison** using various supervised learning algorithms.

---

## 2️⃣ Dataset Information 📂

**Dataset name:** `Final_price_Bob.csv`  
**Total records:** 1000  
**Total features:** 22  

### 🧾 Key Columns

| Feature | Description |
|:--------|:------------|
| `battery_power` | Total energy (mAh) the battery can store |
| `blue` | Bluetooth support (1 = Yes, 0 = No) |
| `clock_speed` | Processor speed in GHz |
| `dual_sim` | Dual SIM support (1 = Yes, 0 = No) |
| `fc` | Front camera megapixels |
| `four_g` | 4G support (1 = Yes, 0 = No) |
| `int_memory` | Internal memory in GB |
| `mobile_wt` | Weight of the mobile (grams) |
| `n_cores` | Number of processor cores |
| `pc` | Primary camera megapixels |
| `px_height` | Pixel height |
| `px_width` | Pixel width |
| `ram` | RAM size (MB) |
| `sc_h` | Screen height |
| `sc_w` | Screen width |
| `talk_time` | Longest talk time (hours) |
| `three_g` | 3G support (1 = Yes, 0 = No) |
| `touch_screen` | Touchscreen availability (1 = Yes, 0 = No) |
| `wifi` | WiFi support (1 = Yes, 0 = No) |
| `Estimated_price_range` | Target variable (0 = Low, 1 = Medium, 2 = High, 3 = Very High) |

---

## 3️⃣ Project Workflow 🛠️

| Step | Description |
|------|-------------|
| **Data Loading** | Load `Final_price_Bob.csv` using Pandas |
| **Data Exploration** | Understand dataset structure, missing values, and relationships |
| **Train-Test Split** | Divide data into training and testing sets |
| **Model Training** | Build and train multiple ML models:<br>• K-Nearest Neighbors (KNN)<br>• Naive Bayes (GaussianNB)<br>• Logistic Regression<br>• Support Vector Machine (SVM) |
| **Model Evaluation** | Compare performance using **accuracy** and **classification report** |
| **Feature Analysis** | Identify most influential features like RAM, battery, and pixel resolution |

---

## 4️⃣ Results & Insights 📈

- Among all models, **SVM** and **KNN** provided the highest accuracy for predicting price ranges.  
- **Top influencing features:** RAM, battery power, and pixel resolution.  
- The model successfully classifies mobiles into one of **four price range categories** (Low, Medium, High, Very High).  

---



