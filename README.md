# 🧠 Deep Learning Midterm — Team Productivity Prediction

A Deep Learning project developed as part of the **Midterm Exam** for the **Deep Learning** course at **BINUS University**.  
This project focuses on building, training, and evaluating multiple **Artificial Neural Network (ANN)** architectures to **predict team productivity scores** in a garment manufacturing factory.

---

## 🎯 Project Goal

Estimate the **productivity score** for each team in a garment factory based on daily operational and performance data.

### Dataset Description
Each record represents one team’s productivity assessment.

| Feature | Description |
|----------|-------------|
| `date` | Date of the assessment |
| `day` | Day of the week |
| `quarter` | Quarter of the year when the data was recorded |
| `team` | Unique identifier for each team |
| `smv` | Standard Minute Value – allocated time for a task |
| `wip` | Work In Progress – number of unfinished products |
| `over_time` | Overtime worked (minutes) |
| `incentive` | Incentive amount (USD) |
| `idle_time` | Idle time of workers (minutes) |
| `idle_men` | Number of idle workers |
| `no_of_style_change` | Number of style changes occurred |
| `no_of_workers` | Total number of workers |
| `productivity_score` | Productivity percentage (target variable) |

---

## 🧩 Project Overview

The project follows a complete **Deep Learning experimentation workflow** using **TensorFlow/Keras**:

1. **Exploratory Data Analysis (EDA)**  
   - Identify missing values, correlations, and data skewness.  
   - Preprocess features and normalize input data.  
   - Split dataset into **Train (70%)**, **Validation (10%)**, and **Test (20%)** sets.  

2. **Model Development**  
   - Built two **baseline ANN models**:  
     - **Sequential Model**  
     - **Functional Model**  
   - Each model includes at least **2 hidden layers** using **ReLU activation**.

3. **Model Modification**  
   - Adjusted neurons, layers, and activation functions.  
   - Performed hyperparameter fine-tuning (e.g., learning rate, batch size, optimizer).  

4. **Evaluation**  
   - Compared four trained models using multiple metrics such as **MAE**, **MSE**, and **R² Score**.  
   - Analyzed training curves and test set performance.  

---

## 🧮 Technologies Used

| Category | Tools |
|-----------|--------|
| **Programming Language** | Python |
| **Frameworks** | TensorFlow, Keras |
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |
| **Dataset Format** | `.parquet` |

---

## 📁 Files Included

| File Name | Description |
|------------|-------------|
| `code.ipynb` | Jupyter Notebook containing model training, tuning, and evaluation |
| `dataset1B.parquet` | Dataset containing team productivity data |
| `README.md` | Project documentation |

---

## 🧾 Evaluation Metrics

The models were evaluated using:
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **R² Score (Coefficient of Determination)**  

---

## 👨‍💻 Author

**Jackie Lim**  
📧 [linkedin.com/in/jackie-lim7/](https://linkedin.com/in/jackie-lim7/)  
🎓 Deep Learning Midterm — BINUS University  
