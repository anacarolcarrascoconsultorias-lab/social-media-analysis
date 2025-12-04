# **Social Media Engagement Analysis**

This project simulates a social media dataset and performs a complete end-to-end data analysis workflow. It includes data generation, exploration, cleaning, visualization, and statistical insights, following industry-standard analytical practices. The goal is to demonstrate proficiency in Python, Pandas, Seaborn, and general data-analysis methodology while preparing a professional-grade portfolio artifact.

---

## 📌 **Project Objectives**

- Generate a synthetic dataset representing social media posts.  
- Load and explore the dataset using Pandas.  
- Clean and prepare the data according to analytical best practices.  
- Visualize engagement distributions and category-level performance.  
- Compute statistical summaries and interpret engagement behavior.  
- Document conclusions and propose future enhancements.

---

## 📂 **Dataset Description**

The dataset is artificially generated using:

- **500 posts**  
- **Date**  
- **Category** (e.g., Food, Travel, Fashion, Music, etc.)  
- **Likes** (random integer between 0 and 10,000)

Since the dataset is synthetic, it allows complete control over structure and variability while remaining realistic enough for practical analysis demonstrations.

---

## 🛠️ **Technologies Used**

- Python 3.x  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Google Colab / Jupyter Notebook  

---

## 🧪 **Methodology**

### **1. Data Generation**

Using Python’s `pandas`, `numpy`, and `random` libraries, the project generates:

- 500 sequential dates  
- 500 randomly selected categories  
- Random like counts between 0 and 10,000  

These components are assembled into a Pandas DataFrame.

---

### **2. Exploratory Data Analysis (EDA)**

Performed structural and statistical review using:

- `df.head()`  
- `df.info()`  
- `df.describe()`  
- Category frequency counts  

Although the dataset contained no missing values, cleaning steps were applied as part of best practices.

---

### **3. Data Cleaning**

- Removed null values  
- Removed duplicate rows  
- Converted `Date` to datetime format  
- Ensured `Likes` column was stored as an integer  

This prepared the dataset for visualization and analysis.

---

### **4. Data Visualization**

Two primary visual techniques were used:

#### 📈 **Histogram — Distribution of Likes**
Visualizes how engagement values are spread across posts.

#### 📦 **Boxplot — Likes by Category**
Compares engagement across content categories and highlights mean values.

Visualizations were created using Seaborn and Matplotlib with clean, portfolio-ready styling.

---

### **5. Statistical Analysis**

- Computed the overall mean of likes  
- Calculated mean likes per category  
- Interpreted engagement variability and category-level performance  

---

## 📊 **Key Insights**

- Like counts show wide variability across posts.  
- No category dominates engagement, though subtle performance differences exist.  
- Engagement metrics can effectively guide content strategy decisions.  
- Synthetic data still demonstrates real-world analytical workflow patterns.

---

## 🧾 **Conclusion**

This project demonstrates an end-to-end analytical workflow, including:

- Data generation  
- Data exploration  
- Data cleaning  
- Visualization  
- Insight extraction  

The workflow reflects professional analytical standards and is suitable for inclusion in a data analytics portfolio.

A detailed written conclusion is included inside the notebook under Task 6.

---

## 🚀 **Future Improvements**

Potential enhancements include:

- Adding extra engagement metrics (comments, shares, sentiment).  
- Incorporating posting time for time-series trends.  
- Creating predictive models for post engagement.  
- Introducing noise to simulate realistic messy data.  
- Developing dashboards with Plotly or Dash.  
- Expanding dataset size for deeper analysis.

---

## ▶️ **How to Run This Project**

1. Clone or download the repository.  
2. Open the notebook in **Google Colab** or **Jupyter Notebook**.  
3. Install required dependencies:

   ```bash
   pip install pandas numpy seaborn matplotlib
4. Run each cell in order.
5. Review visualizations and conclusions at the end of the notebook.

---

## 📁 **Repository Structure**
 ```bash
📦 social-media-analysis
 ┣ 📄 README.md
 ┣ 📄 social-media-analysis.ipynb   
 ┗ 📁 images/

---

👩‍💻 Author

**Ana Carolina Carrasco**
Data Analytics Portfolio Project – 2025
