# Visualization 2: Ontario University Enrolment Overview 

## Tool Used
This visualization was created using **Tableau Public**. The data was cleaned and prepared using **Python (Jupyter Notebook)** and exported as `.csv` files for Tableau ingestion.

## Intended Audience
The intended audience includes:
- **Educational policy-makers** and administrators in Ontario
- **University planners** and institutional researchers
- **Students and the general public** interested in enrolment demographics
- **Equity and inclusion analysts** focusing on gender representation in education

## Message
This dashboard explores **how gender and study level intersect across Ontario's universities**. The goal is to highlight:
- Gender distribution patterns across institutions
- Representation differences between undergraduate and graduate programs
- How credential types (e.g., diploma, degree) vary by gender

## Design Choices
- A **pie chart** provides a quick overview of gender distribution across all Ontario university students
- A **horizontal bar chart** compares graduate vs. undergraduate enrolment by institution
- A **stacked bar chart** breaks down headcount by credential type and gender
- All visuals use **consistent color schemes** to distinguish gender and study levels
- **Interactive filters** for institution, study level, gender, and fiscal year allow custom exploration
- Charts are clearly labeled, and layout is designed for **accessibility and ease of interpretation**

## Reproducibility
- The data was sourced from the [Ontario Open Data Portal](https://data.ontario.ca/dataset/university-enrolment)
- Python code for cleaning and preparing the data is provided in `prepare_dataset.ipynb`
- The cleaned `.csv` files used in Tableau are included
- Final dashboard is **published publicly** and accessible here:  
  [Ontario University Enrolment Overview](https://public.tableau.com/app/profile/iryna.verbova/viz/OntarioUniversityEnrolmentOverview/OntarioUniversityEnrolmentOverview)

## Accessibility
- All charts use **percentage labels**, consistent font sizes, and accessible colors
- Filters enable **user-driven exploration**
- Titles and subtitles offer clear explanations
- Minimal use of clutter or overly complex visuals

## Impacted Communities
This work impacts:
- **Students and their families** making education decisions
- **Educational institutions** that want to analyze gender parity
- **Policy-makers** interested in gender equity
- **Researchers** studying demographic trends in higher education

## Why These Features?
Included features:
- Institution
- Gender
- Study level (Undergraduate / Graduate)
- Credential type
Excluded features:
- Citizenship and first language (to reduce complexity)
- Specific program of study (out of scope for current visual narrative)

## Underwater Labor
Significant effort was required to transform the raw Excel files (multi-sheet, complex structure) into clean, analysis-ready datasets. This involved:
- Loading and inspecting multiple sheets using `pandas`
- Converting fiscal years and text-based numeric values to consistent formats
- Exporting separate `.csv` files for gender and credential views
- Iterating multiple times on Tableau layout, filter logic, and formatting
- Troubleshooting Tableau labels and accessibility controls