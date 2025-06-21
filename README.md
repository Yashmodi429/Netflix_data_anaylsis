# 📊 Netflix Movies and TV Shows - Exploratory Data Analysis (EDA)

This project is an **Exploratory Data Analysis (EDA)** on a dataset containing Netflix Movies and TV Shows information. The analysis aims to understand content trends, genre popularity, vote counts, release years, and more using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📝 Description

Netflix is one of the largest content streaming platforms globally. With thousands of movies and TV shows, it becomes important to analyze its data to gain valuable insights into user preferences, genre popularity, production trends, and more. This project focuses on:
- Understanding how many titles are released per year.
- Which genres dominate the platform.
- Voting patterns across different content.
- Finding hidden patterns and trends using visualizations.

---

## 📁 Files

- `netflix_eda_projext.ipynb`: Main Jupyter Notebook containing the full EDA process and visualizations.
- `README.md`: This file.

---

## 🔍 Analysis Performed

- Top release years by content count.
- Most popular genres by total vote count.
- Distribution of movies and shows.
- Visualization of vote trends over time.
- Use of `value_counts()`, `groupby()`, and plots like bar charts, count plots, etc.

---

## 🛠️ Tools & Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## ▶️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-eda-project.git
   cd netflix-eda-project

	2.	Open the notebook in Jupyter:

jupyter notebook netflix_eda_projext.ipynb


	3.	Run the cells step by step to view data insights and visualizations.

⸻

📌 Sample Code Snippet

year = df['Release_year'].value_counts().idxmax()
count = df['Release_year'].value_counts().max()
print("Year with most movies:", year, "Count:", count)


⸻

✅ Status

✅ Completed initial analysis
🔄 Scope to add more visualizations and machine learning models (recommendations, clustering)

⸻

✍️ Author

Yash Samir Modi
🎓 Student | 📊 Passionate about Data Science and Data Engineering
🛠️ Skills: Python, SQL, EDA, Feature Engineering, Power BI

⸻

📃 License

This project is licensed under the MIT License.

---

Let me know if you want me to:
- Add a section for LinkedIn/GitHub badges
- Add a `requirements.txt`
- Automatically generate this in your GitHub repo
