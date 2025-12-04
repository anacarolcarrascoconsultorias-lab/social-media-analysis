Social Media Engagement Analysis

This project simulates a social media dataset and performs a complete end-to-end data analysis workflow. It includes data generation, exploration, cleaning, visualization, and statistical insights, following industry-standard analytical practices. The goal is to demonstrate proficiency in Python, Pandas, Seaborn, and general data-analysis methodology while preparing a professional-grade portfolio artifact.

📌 Project Objectives

Generate a synthetic dataset representing social media posts.

Load and explore the dataset using Pandas.

Clean and prepare the data according to analytical best practices.

Visualize engagement distributions and category-level performance.

Compute statistical summaries and interpret engagement behavior.

Document conclusions and propose future enhancements.

📂 Dataset Description

The dataset is artificially generated using:

500 posts

Date

Category (e.g., Food, Travel, Fashion, Music, etc.)

Likes (random integer between 0 and 10,000)

Since the dataset is synthetic, it allows complete control over structure and variability while remaining realistic enough for practical analysis demonstrations.

🛠️ Technologies Used

Python 3.x

Pandas

NumPy

Seaborn

Matplotlib

Google Colab / Jupyter Notebook

🧪 Methodology
1. Data Generation

Used Python’s libraries (pandas, numpy, random) to randomly generate:

500 sequential dates

500 categories selected randomly from a predefined list

Random like counts between 0 and 10,000

All values were assembled into a Pandas DataFrame.

2. Exploratory Data Analysis (EDA)

Performed structural and statistical review using:

df.head()

df.info()

df.describe()

Category frequency counts

The dataset showed no missing values but followed through with standard cleaning steps for good analytical practice.

3. Data Cleaning

Applied the following:

Removal of null values

Removal of duplicate rows

Conversion of Date to datetime

Enforcement of integer type for Likes

This ensured consistency prior to visualization and analysis.

4. Data Visualization

Two main visual techniques were used:

Histogram — Distribution of Likes

Shows how engagement values are spread across posts.

Boxplot — Likes by Category

Compares engagement behavior across content categories while highlighting mean values.

Both visualizations use Seaborn and Matplotlib with a clean, professional styling suitable for portfolio purposes.

5. Statistical Analysis

Calculated overall mean of likes

Calculated mean likes per category using Pandas groupby

Interpreted patterns related to engagement variability and category performance

📊 Key Insights

Like counts are widely distributed, indicating high variability in post performance.

No category shows overwhelming dominance, but subtle differences in central tendency and spread highlight potential trends.

The dataset demonstrates how engagement metrics can be compared and summarized to support content strategy.

Even with synthetic data, the workflow mirrors real-world analysis used in digital marketing and social media analytics.

🧾 Conclusion

This project demonstrates end-to-end capability in designing, structuring, and analyzing a dataset using Python. It integrates essential components of data analytics:

Data generation

Exploration

Cleaning

Visualization

Insight extraction

The workflow reflects professional analytical standards and is suitable for inclusion in a data analytics portfolio.

A full written conclusion is included inside the notebook as part of Task 6.

🚀 Future Improvements

Future enhancements may include:

Introducing additional engagement metrics (comments, shares, sentiment).

Incorporating posting time for time-series analysis.

Creating predictive models for post performance.

Simulating more realistic noise and constructing advanced cleaning workflows.

Building interactive dashboards with Plotly or Dash.

Scaling dataset size for more robust statistical analysis.

▶️ How to Run This Project

Clone or download the repository.

Open the notebook in Google Colab or Jupyter Notebook.

Install required dependencies if necessary:

pip install pandas numpy seaborn matplotlib


Run each cell in sequential order.

Review visualizations and conclusions at the end of the notebook.

📁 Repository Structure
📦 social-media-analysis
 ┣ 📄 README.md
 ┣ 📄 social-media-analysis.ipynb   # main notebook
 ┗ 📁 images/                        # optional: exported charts

👩‍💻 Author

Ana Carolina Carrasco
Data Analytics Portfolio Project
2025
