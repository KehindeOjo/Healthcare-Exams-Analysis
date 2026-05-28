# Healthcare Examination Analytics Dashboard

### Regional Candidate Registration & Performance Insights — West Africa

---

## Project Overview

This project analyses candidate registration data for health care professional examinations. It covers over 1,000 candidates across five countries — Nigeria, Ghana, Liberia, Gambia, and Sierra Leone — and provides a structured view of revenue inflows, candidate demographics, exam type distribution, and discipline-level participation.

The goal was to transform a raw registration dataset into an interactive dashboard that gives examination administrators and stakeholders clear, actionable insight at a glance.

---

## Problem

Healthcare examination bodies across West Africa had no centralized system to track candidate registrations, exam revenue, and performance patterns by nationality, discipline, exam type, or gender, limiting administrative oversight and strategic planning.

## Solution

Analysed a 1,000+ candidate registration dataset using Excel, cleaning and structuring data across fields including exam type, faculty discipline, nationality, gender, exam centre, and fee structure. Designed an interactive dashboard with dynamic filters by nationality, exam level, and discipline to surface revenue and candidate distribution insights.

## Impact

Stakeholders gained instant visibility into dominant candidate markets (Nigeria accounting for 84.1% of registrations), revenue concentration by exam tier, gender representation gaps across disciplines, and geographic spread across five countries, enabling faster, evidence-based decisions on pricing, resource allocation, and candidate outreach.

---

## Repository Structure

```
healthcare-exam-analytics/
│
├── HEALTHCARE_EXAMS_ANALYSIS.xlsx   # Raw and cleaned candidate registration dataset
├── Ag_screen_shot.jpg                    # Final dashboard screenshot
└── README.md                             # Project documentation (this file)
```

---

## Dataset Overview

**File:** `HEALTHCARE_2026_EXAMS_ANALYSIS.xlsx`

The dataset contains one record per candidate registration and includes the following key fields:

| Field               | Description                                                    |
| ------------------- | -------------------------------------------------------------- |
| `UserID`            | Unique candidate identifier                                    |
| `status`            | Registration approval status                                   |
| `fname / lname`     | Candidate name                                                 |
| `gender`            | Male or Female                                                 |
| `nationality`       | Country of origin                                              |
| `institution`       | Candidate's affiliated hospital or university                  |
| `examinations`      | Exam level (Associate, Foundation, Specialist)                 |
| `faculty`           | Professional discipline (e.g. Child Health, Clinical Medicine) |
| `exam_centre`       | City where the exam is taken                                   |
| `currency / symbol` | NGN or USD depending on nationality                            |
| `exam_fee`          | Base examination fee                                           |
| `practical`         | Practical component fee (where applicable)                     |
| `dissertation`      | Dissertation component fee (where applicable)                  |
| `viewform`          | Sitting type (firstsitting, resitting, passedboth, etc.)       |

**Total Records:** 1,023 candidates  
**Countries Covered:** Nigeria, Ghana, Liberia, Gambia, Sierra Leone  
**Exam Centres:** Abuja, Ibadan, Enugu, Accra, Banjul

---

## Key Metrics

| Metric                      | Value          |
| --------------------------- | -------------- |
| Total Candidates            | 1,023          |
| Regional Revenue (NGN)      | ₦438.9 Million |
| International Revenue (USD) | $36.2K         |
| Female Candidates           | 571 (55.8%)    |
| Male Candidates             | 452 (44.2%)    |

---

## Dashboard Highlights

The dashboard was built with a clean, monochromatic blue palette for clarity and professionalism. It features four core visualisations:

**Candidates by Exam Type**
Foundation-level exams attract the highest participation at 49.1% (502 candidates), followed by Associate at 28.4% (291) and Specialist at 22.5% (230).

**Candidates by Professional Discipline**
Clinical Medicine leads with 294 candidates (28.7%), followed by Child Health at 273 (26.7%) and Population Health at 243 (23.8%). Primary Care and Behavioural Health make up the remainder.

**Gender Distribution**
Female candidates lead in 4 out of 5 disciplines. The largest gender gap is in Child Health, where females account for an estimated 65%+ of entries.

**Candidates by Nationality**
Nigeria dominates registrations with 860 candidates (84.1%), followed by Ghana at 114 (11.1%), Sierra Leone at 24 (2.3%), Gambia at 21 (2.1%), and Liberia at 4 (0.4%).

---

## Key Insights

1. **Nigeria is the dominant market** — accounting for 84.1% of all registrations by a wide margin. Outreach, logistics, and centre capacity should be weighted accordingly.

2. **Foundation exams drive volume but not revenue** — Foundation attracts the most candidates but carries the lowest fee per candidate, presenting a pricing review opportunity to improve revenue per head.

3. **Female candidates are the majority** — At 55.8% overall, and leading in 4 of 5 disciplines, female participation is a defining characteristic of this cohort and should inform communication and facility planning.

---

## Tool Used

| Tool            | Purpose                                              |
| --------------- | ---------------------------------------------------- |
| Microsoft Excel | Data cleaning, structuring, and exploratory analysis |
| Microsoft Excel | Interactive dashboard design and visualisation       |

---

## How to Use

1. Clone or download this repository.
2. Open `HEALTHCARE_EXAMS_ANALYSIS.xlsx` to explore the raw dataset.
3. Refer to `Ag_screen_shot.jpg` for a snapshot of the final dashboard.
4. The dataset can be imported into Power BI, Tableau, or any BI tool to recreate or extend the dashboard.

---

## Author

**Kehinde Ojo**
Data Analyst
[GitHub Profile](https://github.com/)

---

## License

This project is for portfolio and demonstration purposes. The candidate data has been used strictly for analytical insight and does not expose personally identifiable information beyond what is standard in anonymised exam registration records.
