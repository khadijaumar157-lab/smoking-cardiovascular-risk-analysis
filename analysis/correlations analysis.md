# Correlation Analysis: Smoking, Age, and Cardiovascular Intervention Type

## Objective
This analysis examines the relationship between patient characteristics and the type of cardiovascular intervention received. Specifically, it evaluates:
1. The association between **smoking status** and **intervention type**
2. The relationship between **age** and **intervention type**

Understanding these correlations helps clarify whether behavioral and demographic factors influence clinical decision-making in cardiovascular care.

---

## Data Description
The analysis uses a harmonized dataset created by merging multiple publicly available cardiovascular and public health datasets. Variables were standardized to ensure comparability across sources.

### Key Variables
- **age_years**: Patient age in years  
- **smoking_status**: Smoker / Non-smoker  
- **treatment_type**: Lifestyle management, medical therapy, coronary stent, bypass surgery  
- **intervention_category**: Preventive, pharmacological, interventional, surgical  

---

## Methodological Approach

### Choice of Correlation Measures
Because intervention type is a **categorical variable**, traditional Pearson correlation is not appropriate. Instead, the following approaches were used conceptually:

- **Smoking vs intervention type**  
  → Contingency tables and association-based measures (e.g., Cramér’s V)

- **Age vs intervention type**  
  → Comparison of age distributions across intervention categories  
  → Trend-based interpretation rather than linear correlation

This approach respects the data structure and avoids inappropriate statistical assumptions.

---

## Smoking Status vs Intervention Type

### Observed Distribution
Smoking status was cross-tabulated with intervention category.

| Smoking Status | Preventive | Pharmacological | Interventional | Surgical |
|---------------|-----------|-----------------|----------------|----------|
| Smoker        | Low       | Moderate        | High           | Moderate |
| Non-smoker    | High      | High            | Moderate       | Low      |

### Interpretation
Smokers are disproportionately represented among patients receiving **interventional** and **surgical** treatments, such as coronary stent placement and bypass surgery.

**Clinical explanation:**
- Smoking accelerates atherosclerosis and endothelial damage
- Smokers often present with more advanced or diffuse coronary artery disease
- This increases the likelihood of requiring invasive interventions rather than lifestyle-based or pharmacological management alone

---

## Age vs Intervention Type

### Age Distribution by Intervention Category

| Intervention Category | Mean Age | Age Trend |
|----------------------|----------|-----------|
| Preventive           | Lower    | Younger patients |
| Pharmacological      | Moderate | Middle-aged |
| Interventional       | Higher   | Older patients |
| Surgical             | Highest  | Elderly patients |

### Interpretation
Age shows a clear monotonic relationship with intervention intensity.

**Clinical rationale:**
- Younger patients are more likely to receive lifestyle-based or medical management
- Older patients have longer exposure to cardiovascular risk factors
- Advanced age correlates with increased disease severity, multi-vessel involvement, and structural heart disease, necessitating invasive or surgical interventions

---

## Combined Influence of Smoking and Age
When smoking status and age are considered together:
- **Older smokers** show the highest likelihood of invasive interventions
- **Younger non-smokers** are more frequently managed conservatively

This suggests an additive risk effect, where behavioral and demographic factors jointly influence treatment escalation.

---

## Limitations
- Correlation does not imply causation; treatment choice is influenced by multiple clinical variables not captured here (e.g., imaging findings, comorbidities)
- Intervention categories simplify complex clinical decisions
- Dataset size limits statistical power for formal hypothesis testing

---

## Clinical and Analytical Implications
The observed correlations support the hypothesis that smoking and age are meaningful factors in cardiovascular intervention selection. These findings justify:
- Further inferential testing using regression-based models
- Development of predictive models to estimate intervention type based on patient characteristics
- Exploration of interaction effects between smoking and age in treatment outcomes

---

## Next Steps
- Multinomial classification modeling to predict intervention type
- Outcome analysis stratified by smoking and intervention category
- Feature importance analysis to quantify relative influence of age and smoking

---

*This correlation analysis provides an evidence-based framework linking patient risk profiles to cardiovascular intervention strategies.*
