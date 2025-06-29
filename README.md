# Soccer Team Performance Analysis

## ⚽ Project Overview
This project explores the relationship between soccer team performance and various influencing factors such as player age, overall ratings, match results, and historical achievements. By integrating data from FIFA, UEFA Champions League, and Premier League matches, this project investigates whether player age has a significant impact on overall ratings, and how player attributes connect with team-level success.

Developed as part of Bellevue University's DSC540 Data Preparation course, this project focuses on combining and analyzing real-world data using SQL and Python.

---

## 📂 Data Sources
- **FIFA21 Player Dataset** – Includes player attributes such as age, overall rating, nationality.
- **UEFA Champions League Winners** – Extracted from [Wikipedia](https://en.wikipedia.org/wiki/List_of_European_Cup_and_UEFA_Champions_League_finals)
- **Premier League Match Data** – Acquired from open APIs.

---

## 🛠️ Technologies Used
- SQLite (for relational database creation and SQL joins)
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (joins, filters, data combination queries)
- Jupyter Notebook

---

## 🎯 Key Objectives
- Join and clean data from 3 distinct sources.
- Explore and visualize factors influencing team performance.
- Determine correlation between player age and overall rating.
- Understand attendance patterns, scoring trends, and nationality distributions.

---

## 🔍 Key Visuals and Insights
- **Age vs. Overall Rating**: Players in the 26–30 age range showed the highest average ratings.
- **UEFA Winners by Country**: Nationality data from FIFA was linked to champion clubs.
- **High Scoring Matches**: Premier League data was used to examine goal-scoring patterns.
- **Attendance Trends**: Explored how match popularity varies with league and team.
- **Player Demographics**: Visualized nationality and age group distributions.

---

## 🧩 Data Integration Challenges
- Mismatched formats across datasets (e.g., team names, date formats)
- Merging FIFA nationalities to UEFA winners required thoughtful SQL joins and lookup tables
- Handling missing values, duplicates, and inconsistent labels for accurate insights

---

## 🧠 Skills Demonstrated
- Relational database creation and management
- Data cleaning and transformation with Pandas
- Advanced SQL querying for dataset integration
- Visualization and exploratory analysis using Python

---

## 📁 Project Structure
Soccer-Team-Performance-Analysis/
├── data/
│ ├── fifa_players.csv
│ ├── uefa_winners.csv
│ └── premier_league_api_data.csv
├── database/
│ └── soccer_analysis.db
├── notebooks/
│ └── term_project_analysis.ipynb
├── README.md


---

## 🔒 Ethical Considerations
- Documented all cleaning steps to avoid bias
- Used credible, open-source datasets (FIFA, Wikipedia, official APIs)
- Ensured integrity by noting assumptions and avoiding manipulation of original values

---

## 👤 Author
**Pragathi Porawakara Arachchige**  
Bellevue University – DSC540 Data Preparation  
[GitHub Profile](https://github.com/PragathiM007)
