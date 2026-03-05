# 🌪️ Tornado Trends: 72 Years of U.S. Data (1950–2022)

A self-directed SQL analysis exploring whether tornado frequency, severity, and casualties have changed over seven decades of U.S. weather history.

**Dataset:** NOAA Storm Prediction Center — 72 years of U.S. tornado records

---

## The Questions I Set Out to Answer

1. **Is there a noticeable upward trend in tornado frequency over 72 years?**
2. **Did advances in early warning technology reduce casualties over time?**
3. **Which states experience the most tornadoes on average?**

These questions were self-generated — I wanted to understand whether the data supports the common perception that tornadoes are getting more frequent, and whether better technology has actually saved lives.

---

## Key Findings

**On frequency:** *(add your actual finding here — e.g. "Tornado reports increased significantly from the 1990s onward, likely driven by improved detection rather than a true increase in storm activity")*

**On casualties:** *(add your actual finding — e.g. "Despite more tornado reports, fatalities per event declined steadily after the 1970s, suggesting early warning systems have had a measurable impact on survival")*

**On geography:** *(add your actual finding — e.g. "Texas recorded the highest total tornado count, while Oklahoma led in tornadoes per square mile")*

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| T-SQL (SQL Server) | Data cleaning, EDA, analysis queries |
| NOAA CSV dataset | Raw source data (72 years, ~68,000 records) |

---

## Repository Structure
```
├── Cleaning Tornado CSV.sql         # Data cleaning scripts
├── 01_trend_analysis/               # Frequency over time queries
├── 02_casualty_impact/              # Warning tech vs. casualties
├── 03_state_comparison/             # State-by-state breakdown
└── tornados.csv                     # Source dataset
```

---

## Why This Project

Tornadoes are a topic I've been genuinely curious about since early in my data journey — they're complex, impactful, and the data spans generations. This project pushed me to think like an analyst: start with a real question, find the right data, and let the numbers tell the story.

---

## Author

**Amir Brohi** · [LinkedIn](https://www.linkedin.com/in/amirbrohi/) · [GitHub](https://github.com/Abrohi26)
