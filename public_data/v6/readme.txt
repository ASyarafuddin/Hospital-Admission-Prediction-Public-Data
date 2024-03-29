v6:
- follow v5, cuma handle imbalance class
- include label encoder, normalizer and xgboost data (not handle null)

---------------------------------------------------------------
column count: 88 (include target variable)

train & test before
- tak normalize, tak handle null value,  tak change data type

train & test final
- handle all above

group feature
1- only triage: response var, demogarphics, triage var, chief complaint
2- triage + past med
3- triage + past med + lab
3- full (triage + lab + history)

---------------------------------------------------------------

disposition distribution on training data
- admit: 79% (193,049 data)
- discharge: 21% (51,130 data)