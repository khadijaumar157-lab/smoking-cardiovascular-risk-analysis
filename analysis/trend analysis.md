# Trend Analysis: Evolution of Cardiovascular Treatments Over the Decades

## Objective
The aim of this analysis is to examine how cardiovascular treatment strategies have evolved over time, with a focus on the following:

1. **Surgical interventions** (e.g., coronary artery bypass grafting – CABG)  
2. **Percutaneous interventions** (e.g., stent placement)  
3. **Pharmacological management**  
4. **Preventive and lifestyle-based interventions**  

Understanding trends in treatment allows researchers to contextualize patient outcomes, identify shifts in clinical practice, and inform predictive modeling of intervention strategies.

---

## Data Overview
The trend analysis uses:

- **Processed patient datasets** (merged UCI Heart Disease + cardiovascular health datasets)  
- **Supplementary treatment trend datasets** derived from publicly available literature and health registries (2000–2025)  

### Key Variables

| Variable | Description |
|----------|-------------|
| year | Year of clinical treatment or recorded trend |
| treatment_type | Lifestyle management, medical therapy, stent placement, bypass surgery |
| intervention_category | Preventive, pharmacological, interventional, surgical |
| patient_count | Number of patients receiving each intervention (where available) |
| source | Dataset or literature source |

---

## Methodological Approach

### Standardization of Treatment Categories
To analyze trends, treatment types were harmonized across datasets:

- **Preventive**: Lifestyle modification, exercise, diet counseling  
- **Pharmacological**: Medical therapy, statins, antihypertensives  
- **Interventional**: Percutaneous coronary interventions, stent placement  
- **Surgical**: Coronary artery bypass grafting (CABG), valve surgery  

This ensures comparability across datasets spanning multiple decades and sources.

### Analytical Methods
1. **Aggregation by decade/year**  
   - Count of interventions by category per year/decade  
2. **Proportional analysis**  
   - Percentage of each intervention category relative to total interventions  
3. **Trend visualization (theory)**  
   - Line charts to demonstrate growth/decline in each category  
   - Smoothing to observe long-term trends

---

## Observed Trends

### Surgical Interventions
- **CABG** was the predominant invasive treatment in the 1980s–1990s  
- **Trend**: Slowly decreasing after 2005 as minimally invasive procedures and stents became more common  
- **Driver**: Emergence of percutaneous coronary interventions (PCI), reduced recovery time, lower perioperative risk  

### Percutaneous Interventions
- **Stent placement** emerged in the 1990s and increased sharply  
- **Trend**: Dominant invasive intervention since mid-2000s, particularly drug-eluting stents  
- **Driver**: Reduced restenosis rates, shorter hospital stays, applicability to moderate CAD  

### Pharmacological Management
- **Steady increase** over the decades  
- **Drivers**: Evidence-based medicine supporting statins, ACE inhibitors, beta blockers  
- **Observation**: Even with stent prevalence, medical therapy remains essential for long-term risk reduction  

### Preventive and Lifestyle-Based Interventions
- **Trend**: Gradual increase, particularly post-2010  
- **Drivers**: Public health campaigns, recognition of modifiable risk factors, cost-effectiveness  
- **Observation**: Younger, lower-risk patients are more likely to receive preventive care, while older patients trend toward invasive intervention

---

## Smoking-Specific Insights
- Smokers historically **more likely to receive interventional or surgical treatment**  
- Trend alignment: as awareness of smoking risk increased, early preventive/pharmacological measures gained traction  
- Implication: **Behavioral risk modification programs** have been slowly integrated into standard care

---

## Visual Interpretation (Theory)
To demonstrate trends effectively:

1. **Line Charts**  
   - X-axis: Year/Decade  
   - Y-axis: Percentage of patients per intervention category  
   - Four lines: Preventive, Pharmacological, Interventional, Surgical  

2. **Stacked Area Charts**  
   - Illustrate shifting proportions of interventions over time  
   - Highlights the decline in CABG vs rise of stent placement  

3. **Subgroup Analysis**  
   - Stratify by age or smoking status to examine differential adoption of interventions

---

## Limitations
- Historical patient-level data are incomplete; supplemented literature may have different inclusion criteria  
- Small sample sizes in earlier decades can bias trends  
- Treatment assignment is influenced by local healthcare practices and guidelines, which vary across regions and time  

---

## Clinical and Analytical Implications
- Trend analysis reveals **clear replacement of surgical interventions by percutaneous ones** over the last two decades  
- Preventive and pharmacological strategies are increasingly emphasized  
- These insights can guide:
  - Predictive modeling of intervention type  
  - Health policy decisions and resource allocation  
  - Targeted prevention programs for high-risk populations (e.g., smokers, elderly)

---

## Next Steps
1. Merge trends with patient-level characteristics to model **intervention likelihood over time**  
2. Evaluate **outcome evolution** alongside treatment trends  
3. Explore **interaction effects**: age × smoking × intervention choice

---

*This analysis provides a structured framework to understand how cardiovascular care has evolved over decades, highlighting shifts from invasive surgery to minimally invasive interventions and preventive strategies.*
