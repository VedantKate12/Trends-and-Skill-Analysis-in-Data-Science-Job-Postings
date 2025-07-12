# Trends-and-Skill-Analysis-in-Data-Science-Job-Postings
#  Job Postings & Trends Analysis

This project presents a comprehensive end-to-end **Data Analysis and Visualization** of job postings from various companies across the globe. The focus is on roles related to **Data Science, Artificial Intelligence, and Machine Learning**. The analysis was conducted as a structured 9-day sprint, with each day targeting a specific analytical goal.

---

##  Dataset

The dataset (`cleaned_jobs.csv`) includes cleaned job postings and contains fields such as:

* Job Title
* Company Name
* Location (City, Country)
* Job Description
* Skill flags (e.g., Python, SQL, AWS, etc.)

---

##  Project Highlights

|     Day | Task Focus               | Description                                                                  |
| ------: | ------------------------ | ---------------------------------------------------------------------------- |
|   Day 1 | Data Overview            | Explored dataset structure, shape, columns, and summary statistics           |
|   Day 2 | Data Cleaning            | Removed duplicates, standardized text, and filtered for relevant job titles  |
|   Day 3 | Top Job Titles           | Simplified titles, created bar charts, pie charts, and word clouds           |
|   Day 4 | Top Hiring Companies     | Identified global and India-specific top companies hiring for data roles     |
|   Day 5 | Location Insights        | Analyzed city and country distributions, plotted on bar and interactive maps |
|   Day 6 | Skill Extraction         | Extracted skills using NLP, generated skill word clouds and frequency charts |
|   Day 7 | Skills Across Job Levels | Compared skill demands across entry, mid, and senior levels using heatmaps   |
|   Day 8 | Skill Demand by Company  | Analyzed top companies' demand for specific skills using grouped bar charts  |
|   Day 9 | Final Insights & Summary | Consolidated insights, regional hubs, key skills, roles, and recommendations |


---

##  Tools & Technologies

* **Python**: Pandas, NumPy for data processing
* **Visualization**: Matplotlib, Seaborn, Plotly, Folium,  Wordcloud
* **NLP**: Regex, basic keyword matching,skill extraction(text mining)
* **Jupyter Notebook**: Interactive development and execution

---

## 🔍 Key Insights

* **Most In-Demand Skills**: Python, Excel, SQL remain dominant; AWS and Spark are gaining traction
* **Top Job Roles**: Data Analyst, Data Scientist, and ML Engineer are most advertised
* **Regional Hubs**: India, USA, and Germany lead in job postings; remote opportunities are rising
* **Skill-Level Match**: Entry-level focuses on Excel and SQL, while senior roles demand cloud and deep learning expertise

---

##  Recommendations

* Strengthen core skills: Python, SQL, Excel
* Learn cloud platforms: AWS, Spark
* Target analyst or intern roles initially
* Track trends by region and company
* Include date columns for future time-based trend analysis

---

##  Deliverables

* Cleaned dataset: `cleaned_jobs.csv`
* All visualizations (charts, maps, word clouds)
* Interactive HTML map (top cities in India)
* Final PDF report combining all insights

---

##  How to Run

1. Clone this repository
2. Install required Python libraries
3. Open the notebooks (`Day 1` to `Day 9`) in Jupyter
4. Run cell-by-cell to explore data and generate visualizations


---

##  Acknowledgments

This project was designed as a practical exploration of data trends in the modern job market using Glassdoor job listings. It covers EDA, Visualization, NLP, and Reporting - essential skills for any aspiring Data Analyst or Data Scientist.

---

Feel free to fork, modify, or contribute to improve this analysis!
