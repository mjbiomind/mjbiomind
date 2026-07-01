<img src="BANNER_IMAGE.png" alt="Mary Jacobs Banner" width="100%" />

# Mary Jacobs
### Biostatistics & Health Informatics | Clinical Data Science | AI for Mental Health

Experienced clinical researcher and data analyst specializing in biostatistics, clinical trial data pipelines, and predictive modeling. Bridging the intersection of advanced medical statistics (Stanford) and multi-site clinical trial operations (UCSF) to build reproducible data architectures that disentangle the multi-system biological pathways of PTSD and depression.

[LinkedIn](https://www.linkedin.com/in/mjbiomind/)

---

## 🔬 Scientific Core & Thesis
My long-term research objective is to shift the paradigm of PTSD from a static psychiatric diagnosis to a dynamic, entangled system. I develop reproducible statistical pipelines to isolate, model, and measure interacting biological, behavioral, and socio-environmental pathways.


---

## 🛠️ Ecosystem

- **Core Analytics & Languages:** R (`tidyverse`, `brms`, `ggplot2`), Python (`NumPy`, `Pandas`, `scikit-learn`), SQL, MATLAB
- **Clinical Informatics Infrastructure:** REDCap (Electronic Data Capture), Epic / APeX, OnCore (CTMS), HIPAA & IRB Frameworks
- **Statistical Methodologies:** Causal Inference, Propensity Score Matching, Bayesian Regression, Structural Neuroimaging Preprocessing (SPM12/CAT12, Voxel-Based Morphometry concepts)

- **Data Visualization & Analytics BI:** Power BI, Tableau (Interactive Dashboard Architecture)

---

## 📊 Core Research Portfolio

### 🩺[1. NHANES Causal PTSD Pipeline](https://github.com/mjbiomind/NHANES-Causal-PTSD)

**Objective:** Examine the relationship between chronic stress exposure, inflammation, and PTSD-related outcomes using nationally representative health data.

**Skills**causal inference and complex survey biostatistics

**Research Methods**
- Designed causal inference workflows using inverse probability weighting (IPW) and weighted regression models.
- Evaluated associations between psychosocial stressors and inflammatory biomarkers while accounting for demographic and clinical confounders.
- Produced reproducible statistical analyses using nationally representative NHANES survey data.

**Impact:**
- Isolated specific statistical interaction parameters showing non-linear biological multiplier effects of environmental stress within vulnerable sub-cohorts.
- Replicated robust CDC/NHANES survey designs locally using automated weighting workflows to control for non-random sampling bias.
- Generated publication-ready causal regression visualizations that translate complex multi-variable confounder tables into accessible research insights.

**Tech stack**  `Python` • `pandas` • `NumPy` • `statsmodels` • `Matplotlib`

--

### 🩺[2. Clinical NLP Extraction Pipeline](https://github.com/mjbiomind/clinical-nlp-ptsd)
**Objective:** Transform unstructured clinical notes into structured PTSD symptom data suitable for statistical analysis and machine learning.
**Skills**
**Research Methods**
- Built a rule-based Natural Language Processing (NLP) pipeline to identify PTSD symptom documentation from narrative clinical records.
- Applied medSpaCy and ConText algorithms to distinguish confirmed symptoms from negated, historical, or hypothetical clinical statements.
- Generated research-ready datasets for downstream predictive modeling and clinical outcome analyses.

**Tech stack**   `Python` • `medSpaCy` • `spaCy` • `pandas` • `Matplotlib`
**Impact:**
- Unlocked critical clinical phenotypes buried deep within unstructured textual narratives that standard ICD-10 diagnostic billing codes completely miss.
- Eliminated common text-mining false positives by contextually filtering out negated statements and familial history records.
- Maintained strict operational compliance with data protection standards by engineering a local-first pipeline running entirely on synthetic, de-identified narratives.

---

### 🩺[3. Longitudinal EHR Survival Analysis](https://github.com/mjbiomind/EHR-Survival-PTSD)

**Objective:** Model time-to-diagnosis and clinical progression of PTSD using longitudinal electronic health record (EHR) data.
**Skills** Longitudinal patient timelines and right-censoring modeling skills.
**Research Methods**
- Developed Kaplan–Meier survival analyses to estimate time-to-event outcomes.
- Accounted for right-censored observations resulting from loss to follow-up and administrative study completion.
- Compared survival trajectories across demographic and social risk groups to identify differences in clinical progression.

**Tech stack**   `Python` • `lifelines` • `pandas` • `Matplotlib`
**Impact:**
- Preserved statistical power in longitudinal data by extracting clinical insights from historical patient tracking spans rather than dropping incomplete records.
- Standardized time-to-event methodologies across disparate tracking windows to account mathematically for informative patient dropouts.
- Visualized clear timeline disparities between vulnerable and reference group risk matrices via non-parametric survival probability functions.

---

### 🩺[4. Enterprise OMOP Common Data Model (CDM) ETL Pipeline](https://github.com/mjbiomind/Synthea-OMOP-ETL)

**Objective:** Develop a scalable data engineering pipeline to transform synthetic electronic health record (EHR) data into the OHDSI OMOP Common Data Model (CDM) Version 6.0 for reproducible clinical research and observational health studies.
**Skills** Data engineering, healthcare data harmonization, and production SQL scripting skills.
**Research Methods**
- Designed an Extract, Transform, Load (ETL) pipeline to ingest, validate, and standardize synthetic patient records from multiple source tables.
- Mapped demographic, clinical, and diagnosis data to OMOP CDM standardized vocabularies, including ICD-10-CM and SNOMED CT concepts.
- Built automated data quality checks to ensure consistency and reproducibility throughout the transformation process.
- Implemented an embedded SQLite database to support SQL-based cohort queries and exploratory clinical analyses.
  
**Tech stack**   `Python` • `pandas` • `SQLite` • `SQL` • `OMOP CDM v6.0` • `SNOMED CT`• `ICD-10-CM`
**Impact**
- Produced interoperable, research-ready clinical datasets aligned with international OMOP standards.
- Automated standardized terminology mapping to improve consistency across electronic health record data sources.
- Created a reproducible workflow that supports downstream statistical analysis, cohort discovery, and observational health research.

> *"Using data to understand people, using science to increase happiness, and using knowledge to build a life of lasting impact." -MJBIOMIND*
