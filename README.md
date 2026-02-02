# 💼 Career Event Attendance Cohort Analysis 2025

SQL, Python and Tableau analysis of real event attendance data to identify drivers of no-shows and improve attendance to 40%+.

## Business Context

This project analyses registration and attendance data from a student career event in Australia.
The goal was to understand why attendance was low (29.3%) and to identify data-driven strategies to improve attendance for future events, with a strong focus on cohort behaviour.

## Key Questions

- Does registration timing impact attendance?
- Which countries and universities show higher attendance conversion?
- Are certain study areas more likely to attend?
- How can attendance be increased from 29% to 40%+?

## Tools & Skills

- SQL: joins, aggregations, cohort analysis
- Python: data cleaning and standardisation (pandas)
- Excel: initial data profiling
- Tableau: dashboard and visual storytelling

## Data Preparation

Key data issues addressed:
- Removed cancelled registrations
- Deduplicated multiple ticket purchases per person
- Standardised country and university names
- Encoded attendance as binary (1 = attended, 0 = no-show)

Final dataset: 188 valid registrations.

## Key Insights (Cohort Analysis)

### Registration Timing
- Registrations made 0–6 days before the event showed the highest attendance rate (46%).

### Country Cohorts
- Indian students showed very low attendance conversion (6.7%), despite high registration volume.

### University Cohorts
- University of Sydney achieved a 40% attendance rate, outperforming others.

### Study Area Cohorts
- Business and Marketing cohorts attended at higher rates than IT and Engineering.


## Recommendations

1. Focus marketing efforts within the final 7 days before the event.
2. Send multi-stage reminders to early registrants, including reminders one week and one day before the event.
3. Apply country-specific marketing strategies, for low-conversion cohorts.
4. Prioritise universities with higher attendance conversion.
5. Align event positioning and mentor selection with study areas that demonstrated stronger attendance behaviour.


## Repository Structure

- notebooks/: Python analysis and SQL cohort analysis
- sql/: SQL queries used for analysis
- data/: raw and cleaned datasets
- tableau/: dashboard and screenshots


