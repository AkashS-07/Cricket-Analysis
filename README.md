
#  Cricket Performance Analysis

##  Overview

This project is a **comprehensive cricket performance analysis** based on player statistics from the T20 World Cup. The aim is to extract insights about individual performances using **Python for preprocessing** and **Power BI for visualization**.

Key focus areas include:

* **Batting Performance** (Average, Strike Rate, Boundary %)
* **Bowling Metrics** (Economy, Bowling Strike Rate, Wickets)
* **All-Rounder Analysis**
* **Shortlisting Best Performers Based on Key Metrics**

---

## Project Structure

```
 Cricket-Analysis
├── Cric_Analysis_PreProcessing.ipynb  # Python preprocessing notebook
├── Cric_Analysis_main.pdf             # Power BI report with visuals
├── README.md                          # Project documentation
```

---

##  Technologies Used

* **Python** (Data Cleaning & Transformation)

  * `pandas`, `numpy`, `os`, `json`
* **Power BI** (Interactive Visualization Dashboard)
* **Jupyter Notebook** (for data wrangling and exporting to CSV)
* **T20 JSON Datasets** (source data for all calculations)

---

##  Data Preprocessing

Performed in `Cric_Analysis_PreProcessing.ipynb`:

* Parsed match-level JSON data from T20 games.
* Extracted player-level stats:

  * Total Runs
  * Balls Faced
  * Wickets
  * Economy
  * Dot Ball %
* Computed derived metrics like:

  * **Strike Rate**
  * **Batting Average**
  * **Bowling Strike Rate**
  * **Boundary %**
* Exported clean data to CSVs for use in Power BI.

---

##  Power BI Dashboard Highlights

See `Cric_Analysis_main.pdf` for visual reports. Key visualizations include:

### 1. **Batting Performance**

* Players ranked by Batting Average & Strike Rate.
* Boundary % and Batting Position considered.
* Example: *Suryakumar Yadav* had a Strike Rate of **189.68** and Avg of **59.75**.

### 2. **All-Rounder Contributions**

* Combined metrics of runs, strike rate, wickets, bowling avg.
* Highlighted players like *Marcus Stoinis*, *Glenn Maxwell*, and *Sikandar Raza*.

### 3. **Bowling Metrics**

* Economy and Bowling Strike Rate plotted.
* Example: *Anrich Nortje* had an economy of **5.37** and bowling strike rate of **9.55**.

### 4. **Final XI Selection**

* Based on consolidated metrics, an optimal playing 11 was shortlisted.

---

##  Final Outcome

* A **data-driven selection** of top players for various roles: openers, middle-order, finishers, bowlers, and all-rounders.
* Improved understanding of player efficiency using multiple KPIs.

---
