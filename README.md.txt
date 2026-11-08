# Titanic Survival Analysis

Which factors were linked to survival on the Titanic? An exploratory analysis in Python (pandas, matplotlib, seaborn).

**Open `titanic-analysis.ipynb` for the full walkthrough.**

## Key findings
- Overall survival was **38.4%**.
- **Sex:** women survived at 74.2%, men at 18.9%.
- **Class:** 63.0% (1st), 47.3% (2nd), 24.2% (3rd).
- **Together:** 1st-class women survived at about 97%, 3rd-class men at about 14%.
- **Children (0-12)** had the highest age-group survival, about 58%.

![Sex and class](images/sex_class_heatmap.png)
![Age group](images/survival_by_age_group.png)

## Files
- `titanic-analysis.ipynb`: cleaning, analysis and charts
- `Titanic-Dataset.csv`: raw data
- `titanic_clean.csv`: cleaned data
- `images/`: saved charts

## Limitations
These are associations in the data, not proof of cause. 177 missing ages (20%) were filled with the median, and Cabin was too incomplete to analyse.