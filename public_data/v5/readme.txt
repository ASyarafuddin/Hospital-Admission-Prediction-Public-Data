v5:
- preprocess data as required by UMMC
- include label encoder, normalizer and xgboost data (not handle null)

---------------------------------------------------------------
column count: 88 (include target variable)

train & test before
- tak normalize
- tak handle null value
- tak change data type

train & test final
- done the above

group feature
1- only triage: response var, demogarphics, triage var, chief complaint
2- triage + past medical history
3- triage + past medical history + lab
4- full (triage + past medical history + lab + imaging)

---------------------------------------------------------------

disposition distribution on training data
- admit: 79% (193,049 data)
- discharge: 21% (51,130 data)
