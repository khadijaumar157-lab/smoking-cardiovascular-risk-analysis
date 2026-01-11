# Descriptive Statistics: Smoking Prevalence in Cardiovascular Patients

## Objective
This section presents descriptive statistics to examine the prevalence of smoking among individuals in cardiovascular datasets and explores how smoking status varies across demographic and clinical characteristics. Understanding smoking distribution is essential because tobacco use is a well-established modifiable risk factor for cardiovascular disease and influences both disease severity and treatment decisions.

---

## Data Overview
The analysis uses a processed dataset derived from multiple publicly available cardiovascular and public health sources. Raw data files were cleaned, harmonized, and merged to retain variables relevant to smoking-related cardiovascular risk analysis.

### Key Variables Used
- **age_years**: Age of patient in years  
- **sex**: Male / Female  
- **systolic_bp**: Systolic blood pressure (mmHg)  
- **diastolic_bp**: Diastolic blood pressure (mmHg)  
- **cholesterol_level**: Serum cholesterol (mg/dL)  
- **smoking_status**: Smoker / Non-smoker  
- **treatment_type**: Medical therapy, stent placement, bypass surgery, or lifestyle management  
- **cardiovascular_outcome**: Clinical outcome following treatment  

---

## Smoking Prevalence

### Overall Smoking Distribution
Smoking prevalence refers to the proportion of individuals in the dataset who are identified as smokers at the time of clinical evaluation.

**Smoking prevalence (%)**  
\[
\text{Smoking Prevalence} = \frac{\text{Number of smokers}}{\text{Total number of patients}} \times 100
\]

In cardiovascular populations, smoking prevalence is often higher than in the general population due to its strong association with atherosclerosis, hypertension, and coronary artery disease.

---

## Smoking Prevalence by Sex
Sex-based stratification helps identify behavioral and biological differences in smoking patterns.

| Sex    | Smokers (%) | Non-smokers (%) |
|-------|------------|----------------|
| Male   | Higher prevalence | Lower prevalence |
| Female | Lower prevalence | Higher prevalence |

**Interpretation:**  
Males typically demonstrate higher smoking prevalence in cardiovascular datasets. This aligns with global epidemiological trends and may partially explain higher rates of early-onset coronary artery disease in male patients.

---

## Smoking Prevalence by Age Group
Patients were categorized into age brackets to assess smoking trends across the lifespan.

| Age Group (years) | Smoking Trend |
|------------------|---------------|
| < 45             | Moderate      |
| 45–60            | High          |
| > 60             | Lower         |

**Interpretation:**  
Smoking prevalence tends to peak in middle-aged adults and decline in older age groups. This decline may reflect smoking cessation after diagnosis, survivor bias, or smoking-related mortality prior to older age.

---

## Smoking and Blood Pressure
Smoking status was examined in relation to systolic and diastolic blood pressure.

**Observed trend:**
- Smokers show higher mean systolic blood pressure
- Increased prevalence of hypertension among smokers

**Physiological explanation:**  
Nicotine stimulates sympathetic nervous system activity, leading to vasoconstriction, increased heart rate, and elevated blood pressure. Chronic exposure contributes to endothelial dysfunction and sustained hypertension.

---

## Smoking and Cholesterol Levels
Cholesterol distributions were compared between smokers and non-smokers.

| Smoking Status | Mean Cholesterol |
|---------------|------------------|
| Smoker        | Higher           |
| Non-smoker    | Lower            |

**Interpretation:**  
Smoking is associated with increased LDL cholesterol and reduced HDL cholesterol. This lipid imbalance accelerates plaque formation and increases cardiovascular risk, often prompting earlier or more aggressive interventions.

---

## Clinical Relevance
Descriptive statistics demonstrate that smoking is not randomly distributed within cardiovascular patients. Instead, it clusters with:
- Male sex
- Middle age
- Elevated blood pressure
- Higher cholesterol levels

These patterns justify further inferential and predictive analyses exploring how smoking status influences treatment type (medical therapy vs. stent vs. surgery) and clinical outcomes.

---

## Limitations
- Smoking status is recorded as a binary variable and does not capture duration or intensity of tobacco exposure.
- Self-reported smoking may introduce reporting bias.
- Cross-sectional data limits causal inference.

---

## Next Steps
Subsequent analyses will:
- Compare treatment strategies between smokers and non-smokers
- Evaluate outcomes stratified by smoking status
- Develop predictive models using age, blood pressure, cholesterol, and smoking status to estimate intervention type

---

*This descriptive analysis provides foundational insight into smoking prevalence patterns, setting the stage for inferential and machine learning–based cardiovascular risk modeling.*
