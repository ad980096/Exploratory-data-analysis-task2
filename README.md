# Exploratory-data-analysis-task2
Overview:-This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand data patterns, correlations, missing values, and feature behavior. The goal is to analyze the dataset using statistical summaries and visualizations.

🎯 Objectives
Generate summary statistics (mean, median, std, etc.)
Visualize numeric features using histograms and boxplots
Analyze feature relationships using a correlation matrix
Detect patterns, trends, and anomalies
Make basic feature-level inferences from the data
🧰 Tools & Libraries:-Python,Pandas,NumPy,Matplotlib,Seaborn (only for loading dataset or optional visuals)
📂 Dataset
The project uses the Titanic dataset.
You may load it through Seaborn or use a local titanic.csv.
import seaborn as sns
df = sns.load_dataset("titanic")
Or place titanic.csv in the project folder.
📊 What This Project Includes:-
✔ Summary statistics (numeric & categorical)
✔ Missing value analysis
✔ Histograms for numeric variables
✔ Boxplots grouped by survival
✔ Correlation heatmap
✔ Scatter plots for key features
✔ Categorical value counts
✔ Basic insights like survival rate by sex and class
STRUCTURE:-
├── eda_titanic.ipynb        # Jupyter Notebook with full EDA
├── titanic.csv              # Dataset (if used)
├── titanic_summary.csv      # Generated summary file
└── README.md                # Project documentation

Install required libraries:
pip install pandas numpy matplotlib seaborn
Open the notebook:
jupyter notebook
Run all cells.

📈 Results
The EDA provides:
Key numerical distributions
Relationship between passenger class, gender, age, and survival
Data quality insights (missing values, outliers)
Correlations among numeric features
📬 Author
Project completed as part of a Data Analytics/ML learning task.



