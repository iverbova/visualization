# Visualization 1 – Ontario Health Premium by Taxable Income

## Tool Used
This visualization was created using **Python (Matplotlib)** in a Jupyter Notebook environment.

## Intended Audience
The chart is intended for:
- Ontario residents trying to understand how the health premium applies to them.
- Policy makers evaluating the progressivity of the health premium.
- Data journalism or civic tech audiences who want transparency in government cost structures.

## Message
The visualization illustrates how the **Ontario Health Premium** increases stepwise with an individual's **taxable income**. It communicates the threshold-based structure of this cost — and shows that the burden plateaus after a certain income level.

## Design Choices
- **Step plot** instead of a line plot to reflect the bracketed nature of the premium.
- **Filled area** under the curve to emphasize the cumulative financial burden.
- **Accessible color palette** (indigo + soft fill) for readability and inclusivity.
- **Gridlines and clear axis labels** to guide interpretation.
- **Vertical spacing and layout** to support both screen and print formats.

## Reproducibility
All code and data sources are publicly available:
- Data: [Ontario Open Data Portal](https://data.ontario.ca/dataset/ontario-health-premium-rates)
- Code: Provided in accompanying Jupyter notebook `ohp_income_vs_premium.ipynb`
- Exported image: `ontario_health_premium_plot.png`

## Accessibility
- **High-contrast colors** and **clear text labels** enhance visibility.
- **Step chart format** improves comprehension for cognitive accessibility.
- Data points are labeled for interpretation without hovering or color dependency.
- Chart includes gridlines and a consistent scale.

## Impacted Communities
- Lower-income and middle-income Ontarians are most impacted by this premium.
- The visualization helps illustrate how health-related taxes disproportionately affect certain income groups — relevant for economic justice and advocacy.

## Why These Features?
The premium is based on **income thresholds**, not a continuous rate. Therefore, using a **step plot** preserves policy accuracy. The filled area communicates cost accumulation over time, making the impact more visually intuitive.

## Underwater Labour
- Data cleaning involved parsing non-standard strings like `"From 25,000 to 36,000"` into usable numeric values.
- Ensured fairness in representation by accurately retaining all income groups, including `"Up to 20,000"` and brackets.
- The plot underwent iterative revisions to improve readability, accuracy, and visual appeal.
