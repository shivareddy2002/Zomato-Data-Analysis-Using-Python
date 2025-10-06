<!-- Header Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff4b4b,100:f9c74f&height=180&section=header&text=🍽️%20Zomato%20Data%20Analysis%20Using%20Python&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>
</p>

<p align="center">
  <b>📊 Extracting Business Insights from Zomato’s Restaurant Data using Python</b>
</p>
This project presents a comprehensive analysis of the Zomato restaurant dataset, aiming to extract meaningful business insights using Python. Through effective data cleaning, exploratory data analysis (EDA), and visual storytelling, the notebook uncovers trends in restaurant types, customer preferences, and service patterns across different cities.
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
  <img src="https://img.shields.io/badge/Visualization-Seaborn%20|%20Matplotlib-yellow" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 🎯 **Objective**
The goal of this project is to explore and analyze the **Zomato restaurant dataset** to uncover meaningful trends and patterns that can help businesses make **data-driven decisions**.

Specifically:
- 🧠 Understand data structure & quality  
- 🍜 Identify cuisine and restaurant trends  
- 🌆 Examine ratings & delivery preferences across locations  
- 💸 Analyze cost patterns in different cities

---

## 📌 **Key Features**

### 🧹 Data Cleaning
- Handling null values  
- Removing duplicates  
- Standardizing column formats  
- Filtering irrelevant features

### 📊 Exploratory Data Analysis (EDA)
Answering critical business questions:
- Which cities have the highest number of restaurants?  
- What are the most popular cuisines?  
- How do ratings vary by location and restaurant type?  
- Is online delivery more common in certain areas?  
- What’s the average cost for two across cities?

### 📈 Visualization Tools
- **Matplotlib** & **Seaborn** used for clear, insightful charts and plots.

### 🧠 Data Preprocessing
- Encoding categorical variables  
- Preparing dataset for potential ML modeling

---

## 🧰 **Tech Stack**
- 🐍 Python 3  
- 📊 Pandas, NumPy  
- 📉 Matplotlib, Seaborn  
- 📓 Jupyter Notebook

---

## 📁 **Dataset Overview**
| Column | Description |
|--------|-------------|
| `Restaurant Name` | Name of the restaurant |
| `Location` | City / Area |
| `Cuisines` | Cuisine types served |
| `Average Cost for two` | Cost for two people |
| `Has Online delivery` | Yes / No |
| `Aggregate rating` | Average customer rating |
| `Votes` | Number of user ratings |

> 📌 *Dataset Source: [Kaggle - Zomato Dataset](https://www.kaggle.com/datasets)*

---

## 🧠 **Insights**
Here are some key findings from the analysis:
- 🏙️ **Delhi NCR** has the maximum number of restaurants  
- 🍕 **North Indian** is the most common cuisine  
- ⭐ Ratings tend to be higher for fine dining than for cafés  
- 🛵 Online delivery is more popular in metropolitan areas  
- 💰 Average cost for two varies significantly between cities

---

## 🛠️ **How to Run Locally**
```bash
# Clone the repository
git clone https://github.com/yourusername/Zomato-Data-Analysis-Using-Python.git

# Navigate to the project folder
cd Zomato-Data-Analysis-Using-Python

# Install required libraries
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook
