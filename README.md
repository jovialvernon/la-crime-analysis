# Analyzing Crime in Los Angeles

> **Note:** This project is based on a guided DataCamp challenge. All code, analysis, and insights here are my own.

---

## Project Objective

Analyze crime records from Los Angeles to identify patterns in criminal activity by hour, location, and victim age group. The goal is to summarize trends that could support more effective public safety resource planning.

---

## Questions Answered

1. Which hour of the day has the highest crime frequency?
2. Which area has the most crimes during late-night hours?
3. How are crimes distributed across victim age brackets?

---

## Dataset Information

**Dataset:** `crimes.csv`

The dataset contains Los Angeles crime records with columns for report date, occurrence date, time, area name, crime description, victim age, victim sex, victim descent, weapon description, status, and location.

---

## Key Results

- **Peak crime hour:** 12:00
- **Crimes at peak hour:** 13,663
- **Highest late-night crime location:** Central
- **Late-night crimes in Central:** 3,312
- **Largest victim age group:** 26-34

---

## Tools Used

- Python
- pandas
- numpy
- seaborn
- matplotlib
- Jupyter Notebook

---

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/jovialvernon/la-crime-analysis.git
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements
   ```

3. Open the notebook:
   ```bash
   jupyter notebook la_crime_analysis.ipynb
   ```
