# 🎬 Netflix Data Visualization Project

This project explores the **Netflix Movies and TV Shows Dataset** using **Python**, focusing on **data cleaning, analysis, and visualizations**. It demonstrates how to use libraries such as **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly** to gain insights from real-world datasets.

---

## 📘 Project Overview

The dataset contains information about movies and TV shows available on Netflix, including details like title, director, cast, country, release year, rating, and duration.  
The goal of this notebook is to:
- Clean and preprocess the dataset  
- Perform exploratory data analysis (EDA)  
- Visualize patterns using different chart types  
- Create **interactive visualizations** for deeper exploration  

---

## 🧰 Technologies Used

| Category | Tools/Libraries |
|-----------|----------------|
| Data Handling | `pandas`, `numpy` |
| Data Visualization | `matplotlib`, `seaborn`, `plotly` |
| Environment | Google Colab / Jupyter Notebook |
| Dataset | `netflix_titles.csv` |

---

## 📊 Visualizations Performed

### 🔹 **Basic Charts (Matplotlib)**
- **Bar Chart** – Diagnosis (Type) Counts  
- **Histogram** – Distribution of movie durations or release years  
- **Line Chart** – Year-wise content release trend (first 50 entries)

### 🔹 **Seaborn Categorical Plots**
- **Box Plot** – Visualizing rating distribution  
- **Violin Plot** – Duration by type (Movie/TV Show)  
- **Count Plot** – Count of Movies vs. TV Shows  

### 🔹 **Interactive Plots (Plotly)**
- **Interactive Scatter Plot** – Release Year vs. Duration  
- **Interactive Histogram** – Distribution of content by year  

---

## 📂 Project Structure

Netflix_Data_Visualization/
├── netflix_titles.csv # Dataset file
├── netflix_visualization.ipynb # Main Colab/Jupyter notebook
├── README.md # Project documentation

---

##  How to Run the Project

### Option 1: Run on **Google Colab**
1. Upload `netflix_visualization.ipynb` and `netflix_titles.csv` to Colab.
2. Run each cell sequentially.
3. Visualizations will appear inline.

### Option 2: Run Locally
bash
# Clone this repository
git clone https://github.com/<your-username>/netflix-data-visualization.git
cd netflix-data-visualization

# Install dependencies
pip install pandas matplotlib seaborn plotly

# Open the notebook
jupyter notebook netflix_visualization.ipynb
