# Data Dictionary

| Variable                 | Description                                          | Type        |
|:-------------------------|:-----------------------------------------------------|:------------|
| ESQUEMA NIVEL 1          | Therapy scheme and level                             | categorical |
| EDAD                     | Age of the patient (years)                           | integer     |
| SEXO                     | Sex of the patient                                   | categorical |
| IMC                      | Body Mass Index (BMI)                                | float       |
| EPWORTH BASAL            | Baseline Epworth Sleepiness Scale score              | integer     |
| EPWORTH SALIDA           | Post-treatment Epworth Sleepiness Scale score        | integer     |
| PuntGeneral              | General effectiveness score (patient perception)     | float       |
| SINTOMAS BASALES         | Reported baseline symptoms                           | text        |
| SINTOMA PRINCIPAL        | Main reported symptom                                | text        |
| TIPO EXAMEN DE SUEÑO     | Type of sleep study performed (e.g., PSG, PLG)       | categorical |
| IAH BASAL                | Baseline Apnea-Hypopnea Index (AHI)                  | float       |
| INDICE DE RONQUIDO/h     | Snoring index (events/hour)                          | float       |
| % SpO2                   | Average peripheral oxygen saturation                 | float       |
| MÍNIMAS DE O2            | Minimum oxygen saturation                            | float       |
| T 90                     | T90: % of time with O2 saturation < 90%              | float       |
| ANTC QX EN VAS           | History of upper airway surgery                      | boolean     |
| CUAL (ES)                | Details of previous surgeries (if any)               | text        |
| OVAS                     | History of upper airway obstruction diagnosis        | boolean     |
| LENG RETRAÍDA            | Retracted tongue (clinical observation)              | boolean     |
| UVULA ALARGADA           | Elongated uvula (clinical observation)               | boolean     |
| VELO DESCENDIDO          | Descended soft palate (clinical observation)         | boolean     |
| PILARES ERITEMATOSOS     | Erythematous palatine pillars (clinical observation) | boolean     |
| MAN BOSTEZO - VELO       | Velum response during yawning                        | text        |
| MAN BOSTEZO - ÚVULA      | Uvula response during yawning                        | text        |
| MAN. FONEMA - VELO       | Velum response during phoneme production             | text        |
| MAN FONEMA - ÚVULA       | Uvula response during phoneme production             | text        |
| SIG. MASTICACIÓN         | Signs of masticatory dysfunction                     | boolean     |
| SIG DE DEGLUCIÓN         | Signs of swallowing dysfunction                      | boolean     |
| CO_Cardiovasculares      | Presence of cardiovascular comorbidities             | boolean     |
| CO_Endocrino_metabólicas | Presence of endocrine-metabolic comorbidities        | boolean     |
| CO_Psiquiátricas         | Presence of psychiatric comorbidities                | boolean     |
| CO_Pulmonares            | Presence of pulmonary comorbidities                  | boolean     |
| Línea_media_desviada     | Deviated dental midline                              | boolean     |
| Mordida_borde_a_borde    | Edge-to-edge bite                                    | boolean     |
| Mordida_abierta_anterior | Anterior open bite                                   | boolean     |
| Mordida_cruzada          | Crossbite                                            | boolean     |
| Maloclusión_clase_II     | Class II malocclusion                                | boolean     |
| Maloclusión_clase_III    | Class III malocclusion                               | boolean     |