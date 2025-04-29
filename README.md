# 📺 Netflix Titles — Exploratory Data Analysis (EDA)

This project explores and analyzes Netflix’s catalog of TV shows and movies using a public dataset from Kaggle. The aim was to extract insights into content types, genre distributions, country trends, and historical growth, while practicing data cleaning, EDA, and visualization techniques using Python.


## 📌 Project Goals

- Perform initial data cleaning and preprocessing.
- Analyze the distribution of Movies vs TV Shows.
- Discover the most frequent content-producing countries.
- Visualize content trends by year and genre.
- Generate actionable business insights from raw data.


## 🧰 Tools & Technologies

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- Jupyter Notebook
- Dataset Source: [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)


## 🧼 Data Cleaning Summary

- Dropped 14 rows with missing `date_added` or `rating`.
- Filled missing values in `director`, `cast`, `country`, and `duration` with `"Unknown"`.
- Extracted `year_added` from the `date_added` field.


## 📈 Key Visualizations

- Movies vs TV Shows count distribution
- Top 10 countries by content production
- Titles added per year trend (growth pattern)


## 🔍 Key Insights

- Movies represent around 70% of Netflix content.
- The United States, India, and the UK are the top content-producing countries.
- Drama, Comedies, and International Movies are the most frequent genres.
- New content additions peaked in 2019, showing rapid growth before the pandemic.


## 📂 Folder Structure

Netflix_EDA_Project/ │ ├── netflix_titles.csv ├── Netflix_EDA.ipynb └── README.md



## 📄 Project Status

✅ Completed core EDA  
🔜 Future upgrades: Build a dashboard version using Tableau or Streamlit


## 🙋‍♂️ Author

Sammy S. Mutuku  
📍 Aspiring Data Scientist  | Data Analyst 

🔗 [GitHub](https://github.com/subu53) | 
[LinkedIn](https://www.linkedin.com/in/samsubu/)




