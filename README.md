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

**On frequency: Tornado reports increased significantly from the 1950s through the 1990s, but most researchers attribute this to better detection equipment (Doppler radar rollout in the early 90s) and more trained storm spotters — not necessarily more actual tornadoes. The raw count roughly tripled over the period.

**On casualties: Despite more reported tornadoes, fatalities per event dropped dramatically after the 1970s. The introduction of the NOAA Weather Radio system and later smartphone alerts made a measurable difference. Peak death years were in the 1950s–60s. By the 2000s, annual fatalities were a fraction of what they were per storm.

**On geography: Texas has the highest total tornado count by a wide margin. But Oklahoma and Kansas lead when adjusted for land area — the classic "Tornado Alley." Florida surprisingly ranks high in total count due to weak but frequent tornadoes from thunderstorms.

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
