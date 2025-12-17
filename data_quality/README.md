# Data Quality Assessment

## Overview
This section focuses on evaluating and improving the quality of the student performance dataset before conducting any statistical analysis.

High-quality data is essential to ensure reliable insights and avoid misleading conclusions.

---

## Objectives
- Assess the cleanliness and reliability of the dataset
- Identify potential data quality issues
- Decide whether detected issues represent data errors or real-world phenomena

---

## Data Quality Dimensions

### 1. Validity
- Checked whether values follow allowed formats and ranges
- Ensured exam scores fall within valid boundaries
- Verified appropriate data types (numerical vs categorical)

### 2. Accuracy
- Assessed whether values realistically reflect student performance
- Investigated extreme values and determined they represent actual low-performing students rather than data entry errors

### 3. Completeness
- Calculated the proportion of missing values across features
- Evaluated whether missing data could impact analysis results

### 4. Consistency
- Ensured uniform formatting (units, naming, capitalization)
- Verified internal consistency across related fields

---

## Key Findings
- No critical validity violations detected
- Extreme low scores were meaningful and retained
- Missing values were minimal and manageable
- Dataset was suitable for further statistical analysis

---

## Notebook Reference
Detailed checks and analysis can be found in:
- `notebooks/Dirtness.ipynb`

---

## Next Steps
- Proceed with exploratory data analysis
- Apply statistical tests to assess performance differences
- Document insights with clear data-driven explanations
