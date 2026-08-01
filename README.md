# Project: Expectation Decider

**Course:** Mathematics & Advanced Statistics
**Institute:** Red & White Skill Education
**Role:** Junior Data Analyst

## Project Objective

The institute is launching a new "Expectation Decider" model that predicts whether a student will pass a competitive mathematics exam based on historical data. This project analyzes probability patterns from a sample dataset of 200 students to derive meaningful insights using core probability concepts.

## Dataset

`expectation_decider.csv` — 200 student records with the following fields:

| Field | Description |
|---|---|
| `study_hours` | Number of hours a student studied per week |
| `attendance` | Percentage attendance in lectures |
| `group_discussion` | Participation in group discussions (Yes/No) |
| `previous_test_score` | Marks out of 100 from the last internal test |
| `final_exam_pass` | Whether the student passed the competitive exam (Pass/Fail) |

## Repository Contents

```
├── Expectation_Decider_Analysis.ipynb   # Full analysis notebook (theory + code)
├── expectation_decider.csv              # Source dataset (200 students)
├── Expectation_Decider_Report.pdf       # Theory pages (photographed/exported notebook)
└── README.md                            # This file
```

## Analysis Covered in the Notebook

1. **Understanding the Basics** — Definition of probability, key terminology, and three probability event examples drawn from the dataset.
2. **Types of Events** — One empirical and one theoretical probability scenario, each calculated.
3. **Random Variable & Probability Distribution** — Binomial distribution for "number of students passing out of 3 randomly selected," with a full distribution table, mean, and variance.
4. **Venn Diagram** — Overlap between students who study more than 10 hrs/week and students who attend more than 80% of classes.
5. **Contingency Table & Probability Calculations** — Joint, marginal, and conditional probability of passing vs. group discussion participation.
6. **Understanding Relationships** — Plain-language interpretation of conditional probability, and a test for independence / dependence / mutual exclusivity between group discussion participation and passing.
7. **Bayes' Theorem Application** — Calculating P(Pass | High Attendance) using given historical conditional probabilities.

Each section includes worked formulas, step-by-step calculations, and supporting tables/charts, concluding with a final summary of the factors that most affect a student's probability of passing.

## How to Run

1. Clone this repository.
2. Ensure `expectation_decider.csv` is in the same folder as the notebook.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib
   ```
4. Open and run the notebook:
   ```bash
   jupyter notebook Expectation_Decider_Analysis.ipynb
   ```
   (All cells are already pre-executed, so outputs are visible without re-running — but it can be re-run top to bottom to reproduce results.)

## Video Walkthrough

📹 **Video link:** [Add your Google Drive / YouTube unlisted link here]

The video (5–10 minutes) walks through every task in the notebook with face + screen recording, explaining the reasoning behind each calculation.

## Author

**Name:** [Add your name]
**Submission:** PR1_[YourName]_GRID

---
*"Quality is our Motto." — Red & White Skill Education*
