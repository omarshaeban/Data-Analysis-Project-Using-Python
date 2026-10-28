# Data Science Salaries — Exploratory Data Analysis with Python

An academic exploratory data analysis (EDA) project examining salary patterns across data-related roles using **Python, pandas, NumPy, seaborn, matplotlib, and Plotly**.

## Project overview

The project analyzes the `ds_salaries.csv` dataset, exploring how salary levels vary by **job title, experience level, employment type, company size, work arrangement, and company location**. The repository contains the original Jupyter notebook and its supporting dataset.

## Dataset and preparation

- **Dataset:** `ds_salaries.csv`
- **Source fields examined:** `salary_in_usd`, `experience_level`, `employment_type`, `remote_ratio`, `job_title`, `company_size`, `company_location`, and `work_year`.
- **Preparation:** Expanded category abbreviations into readable labels, checked for duplicate entries, removed duplicates, dropped redundant salary-related columns, and inspected missing values.
- **Recorded analysis size:** The notebook's saved output shows **2,584 rows after deduplication** and 9 columns. This is the historical notebook output, not a fresh independent rerun.

## Analysis questions

1. Which job titles have the highest mean salaries in the dataset?
2. How does salary distribution differ by experience level?
3. What is the overall distribution of salaries in USD?
4. How does employment type relate to average salary?
5. How do mean salaries compare across company sizes?
6. How common are on-site, remote, and hybrid arrangements?
7. Which company locations appear most frequently under remote-work arrangements?

## Methods and visualizations

The notebook includes descriptive statistics, categorical recoding, duplicate removal, grouped means and medians, and visualizations such as bar plots, box plots, histograms, a bubble/scatter chart, and a pie chart. The analysis is descriptive: it does **not** establish causation or prove that any employment factor directly determines salary.

## Files

- `ds_salaries.csv` — dataset used by the notebook.
- `(مشروع مساق لغة برمجة علم البيانات (عملي.ipynb` — original academic Jupyter notebook (Arabic filename).
- `README.md` — this project overview.

## Reproduce locally

```bash
python -m pip install pandas numpy matplotlib seaborn plotly notebook
jupyter notebook
```

Open the notebook from this repository and run cells in order. Use the CSV in the same directory as the notebook.

## Limitations

- This is an **academic analysis**, not an employment compensation benchmark or a predictive model.
- Salaries are historical observations from the provided dataset; year, geography, occupation and sample composition all affect comparisons.
- Group averages can be misleading where sample counts vary, so interpret results alongside distribution and group size.
- The notebook includes group-project attribution to its original contributors; preserve attribution when presenting the work.
