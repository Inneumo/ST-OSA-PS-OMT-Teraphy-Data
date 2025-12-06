# Data Dictionary

This data dictionary provides concise descriptions for each column in `data/data_es.csv`. Entries include the column name as in the CSV (original Spanish header), an English long name, data type, a short description, unit/range when applicable, variable type, and a brief example.

## Columns

1. **ESQUEMA NIVEL 1**
   - **Long Name**: Level 1 Treatment Scheme
   - **Data Type**: Categorical (string)
   - **Description**: Treatment scheme used at the start of Orofacial Myofunctional Therapy (e.g., `TMO NIVEL 1`, `TMO NIVEL 1 TCC`).
   - **Unit/Range**: `TMO NIVEL 1` / `TMO NIVEL 1 TCC`
   - **Variable Type**: Categorical
   - **Example**: `TMO NIVEL 1 TCC`

2. **EDAD**
   - **Long Name**: Age (years)
   - **Data Type**: Numeric (integer/float)
   - **Description**: Patient age in years at start of treatment.
   - **Unit/Range**: Years (e.g., 18–75+)
   - **Variable Type**: Continuous
   - **Example**: `37`

3. **SEXO**
   - **Long Name**: Sex / Gender
   - **Data Type**: Categorical (string)
   - **Description**: Biological sex of the patient (Spanish labels in file: `FEMENINO`, `MASCULINO`).
   - **Unit/Range**: `FEMENINO` / `MASCULINO`
   - **Variable Type**: Categorical
   - **Example**: `FEMENINO`

4. **IMC**
   - **Long Name**: Body Mass Index (BMI)
   - **Data Type**: Numeric (float)
   - **Description**: Body mass index calculated as weight (kg) / height (m)^2.
   - **Unit/Range**: kg/m² (example values in dataset ~18.4–39)
   - **Variable Type**: Continuous
   - **Example**: `21.8`

5. **EPWORTH BASAL**
   - **Long Name**: Epworth Sleepiness Scale (baseline)
   - **Data Type**: Numeric (integer)
   - **Description**: Baseline Epworth score (0–24) before treatment.
   - **Unit/Range**: 0–24
   - **Variable Type**: Ordinal/Continuous
   - **Example**: `12`

6. **EPWORTH SALIDA**
   - **Long Name**: Epworth Sleepiness Scale (exit)
   - **Data Type**: Numeric (integer)
   - **Description**: Epworth score at end of treatment.
   - **Unit/Range**: 0–24
   - **Variable Type**: Ordinal/Continuous
   - **Example**: `10`

7. **PuntGeneral**
   - **Long Name**: General Score / Overall Rating
   - **Data Type**: Numeric (float)
   - **Description**: General summary score or patient global score (dataset-specific scale).
   - **Unit/Range**: Typically 0–5 (see dataset values)
   - **Variable Type**: Ordinal
   - **Example**: `4`

8. **SINTOMAS BASALES**
   - **Long Name**: Baseline Symptoms
   - **Data Type**: Categorical (string)
   - **Description**: Short label describing primary baseline symptoms (e.g., `Cansancio crónico`, `Ronquido`).
   - **Variable Type**: Categorical
   - **Example**: `Cefalea matutina`

9. **SINTOMA PRINCIPAL**
   - **Long Name**: Main Symptom
   - **Data Type**: Categorical (string)
   - **Description**: The principal complaint reported by the patient at baseline.
   - **Variable Type**: Categorical
   - **Example**: `Sueño no reparador`

10. **TIPO EXAMEN DE SUEÑO**
   - **Long Name**: Type of Sleep Test
   - **Data Type**: Categorical (string)
   - **Description**: Type of diagnostic sleep study performed (e.g., `PSG`, `PLG`).
   - **Unit/Range**: `PSG` / `PLG` / `PLG` variants
   - **Variable Type**: Categorical
   - **Example**: `PSG`

11. **IAH BASAL**
   - **Long Name**: Baseline Apnea–Hypopnea Index (AHI)
   - **Data Type**: Numeric (float)
   - **Description**: AHI measured at baseline (events per hour).
   - **Unit/Range**: events/hour
   - **Variable Type**: Continuous
   - **Example**: `9.8`

12. **INDICE DE RONQUIDO/h**
   - **Long Name**: Snoring Index (events per hour)
   - **Data Type**: Numeric (float)
   - **Description**: Index measuring snoring events per hour.
   - **Unit/Range**: events/hour
   - **Variable Type**: Continuous
   - **Example**: `11.7`

13. **% SpO2**
   - **Long Name**: Mean/average peripheral oxygen saturation
   - **Data Type**: Numeric (float)
   - **Description**: Mean SpO2 or percent saturation recorded during study (values in dataset are decimals like 0.94 representing 94%).
   - **Unit/Range**: 0–1 (decimal) or 0–100% if scaled
   - **Variable Type**: Continuous
   - **Example**: `0.94` (94%)

14. **MÍNIMAS DE O2**
   - **Long Name**: Minimum SpO2
   - **Data Type**: Numeric (float)
   - **Description**: Minimum oxygen saturation recorded during the sleep study.
   - **Unit/Range**: 0–1 (decimal) or percentage
   - **Variable Type**: Continuous
   - **Example**: `0.78`

15. **T 90**
   - **Long Name**: Time Spent with SpO2 < 90%
   - **Data Type**: Numeric (float)
   - **Description**: Proportion/seconds/minutes the patient spent below 90% saturation (dataset specific).
   - **Unit/Range**: Fraction or proportion in dataset
   - **Variable Type**: Continuous
   - **Example**: `0.06`

16. **ANTC QX EN VAS**
   - **Long Name**: Prior Airway Surgery (Yes/No)
   - **Data Type**: Categorical (string)
   - **Description**: Whether the patient has prior surgeries in the upper airway (`SI`/`NO`).
   - **Variable Type**: Categorical
   - **Example**: `NO`

17. **CUAL (ES)**
   - **Long Name**: Which Surgery (Details)
   - **Data Type**: Text (string)
   - **Description**: Free text listing prior surgical procedures (e.g., `Amigdalectomía`, `Septoplastia`).
   - **Variable Type**: Categorical / Free text
   - **Example**: `Amigdalectomía, Septoplastia`

18. **OVAS**
   - **Long Name**: OVAS (clinical label)
   - **Data Type**: Categorical (string)
   - **Description**: Clinical flag used by the study (dataset-specific). Keep raw values for analysis.
   - **Variable Type**: Categorical
   - **Example**: `NO`

19. **LENG RETRAÍDA**
   - **Long Name**: Retracted Tongue
   - **Data Type**: Categorical (Yes/No/qualifier)
   - **Description**: Clinical observation indicating retracted tongue posture.
   - **Variable Type**: Categorical
   - **Example**: `NO`

20. **UVULA ALARGADA**
   - **Long Name**: Elongated Uvula
   - **Data Type**: Categorical
   - **Description**: Presence of an elongated or enlarged uvula on exam.
   - **Variable Type**: Categorical
   - **Example**: `NO`

21. **VELO DESCENDIDO**
   - **Long Name**: Lowered Soft Palate
   - **Data Type**: Categorical
   - **Description**: Clinical sign of a descended soft palate.
   - **Variable Type**: Categorical
   - **Example**: `SI`

22. **PILARES ERITEMATOSOS**
   - **Long Name**: Erythematous Pillars
   - **Data Type**: Categorical
   - **Description**: Presence of redness/inflammation in the palatal pillars.
   - **Variable Type**: Categorical
   - **Example**: `SI`

23. **MAN BOSTEZO - VELO**
   - **Long Name**: Mano Bostezo - Soft Palate Movement
   - **Data Type**: Categorical / Text
   - **Description**: Observation of soft palate movement during yawn maneuver (qualitative descriptor).
   - **Variable Type**: Categorical
   - **Example**: `Asciende el velo reducido`

24. **MAN BOSTEZO - ÚVULA**
   - **Long Name**: Mano Bostezo - Uvula Movement
   - **Data Type**: Categorical / Text
   - **Description**: Uvula movement observed during yawn maneuver.
   - **Variable Type**: Categorical
   - **Example**: `No contrae la úvula`

25. **MAN. FONEMA - VELO**
   - **Long Name**: Phoneme Maneuver - Soft Palate
   - **Data Type**: Categorical / Text
   - **Description**: Soft palate response during phonation tests (qualitative).
   - **Variable Type**: Categorical
   - **Example**: `Asciende el velo reducido`

26. **MAN FONEMA - ÚVULA**
   - **Long Name**: Phoneme Maneuver - Uvula
   - **Data Type**: Categorical / Text
   - **Description**: Uvula response during phonation tests.
   - **Variable Type**: Categorical
   - **Example**: `Contrae la úvula totalmente`

27. **SIG. MASTICACIÓN**
   - **Long Name**: Mastication Signs
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of abnormal mastication patterns on exam.
   - **Variable Type**: Categorical
   - **Example**: `SI`

28. **SIG DE DEGLUCIÓN**
   - **Long Name**: Swallowing Signs
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Signs of altered swallowing observed during exam.
   - **Variable Type**: Categorical
   - **Example**: `SI`

29. **CO_Cardiovasculares**
   - **Long Name**: Cardiovascular Comorbidities
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of cardiovascular comorbid conditions.
   - **Variable Type**: Categorical
   - **Example**: `NO`

30. **CO_Endocrino_metabólicas**
   - **Long Name**: Endocrine / Metabolic Comorbidities
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Diabetes, dyslipidemia, thyroid disorders, etc.
   - **Variable Type**: Categorical
   - **Example**: `NO`

31. **CO_Psiquiátricas**
   - **Long Name**: Psychiatric Comorbidities
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of psychiatric diagnoses.
   - **Variable Type**: Categorical
   - **Example**: `NO`

32. **CO_Pulmonares**
   - **Long Name**: Pulmonary Comorbidities
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Respiratory diseases such as COPD, asthma.
   - **Variable Type**: Categorical
   - **Example**: `NO`

33. **Línea-media_desviada**
   - **Long Name**: Midline Deviation
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Dental/craniofacial midline deviation on exam.
   - **Variable Type**: Categorical
   - **Example**: `NO`

34. **Mordida_borde_a_borde**
   - **Long Name**: Edge-to-edge Bite
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Dental occlusion type: edge-to-edge contact.
   - **Variable Type**: Categorical
   - **Example**: `NO`

35. **Mordida_abierta_anterior**
   - **Long Name**: Anterior Open Bite
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of open bite in anterior dentition.
   - **Variable Type**: Categorical
   - **Example**: `NO`

36. **Mordida_cruzada**
   - **Long Name**: Crossbite
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of crossbite.
   - **Variable Type**: Categorical
   - **Example**: `NO`

37. **Maloclusión_clase_II**
   - **Long Name**: Malocclusion Class II
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of Angle Class II malocclusion.
   - **Variable Type**: Categorical
   - **Example**: `SI`

38. **Maloclusión_clase_III**
   - **Long Name**: Malocclusion Class III
   - **Data Type**: Categorical (Yes/No)
   - **Description**: Presence of Angle Class III malocclusion.
   - **Variable Type**: Categorical
   - **Example**: `NO`

## Notes

- The dataset columns are provided in Spanish as recorded in `data/data_es.csv`. Use the original column names when writing analysis scripts to avoid mismatches.
- Some clinical fields contain free-text qualifiers (e.g., `CUAL (ES)`, maneuver descriptions). Consider cleaning/standardizing these before categorical aggregation.
- Oxygen saturation fields are represented as decimals in the CSV (e.g., `0.94` = 94%). Verify scaling when plotting or computing thresholds.
- If you want, I can produce an English-only version, or generate a CSV mapping file `column_map.csv` that maps original headers to short English variable names for analysis.



