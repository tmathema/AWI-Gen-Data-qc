# AWI-Gen-Data-qc

`Age_recalculation.py` is used to recalculate phase 1 age based on date of birth provided in phase 2.

`analysis_class_phase2.py` contains all python code functions used to produce data for all calculated variables in phase 2.

`awigen_2_data_database.py` is used to merge all the sites REDCap data to form a single file for upload on SQL.

`continousvar_qc.py` is used identify outliers between phases 1 and 2 continous data.

`logic.py` is used to encode -555 (not applicable) based on the branching logic on the questionaire.

`plots_sites.py` is used to produce the pdf outputs for phase 1 and 2 continous data comparisons.

`site_summaries_phase2.py` is used to produce data distributions for all categorical variables in phase 2.

`main.py' Main file for producing the Excel sheet containing outliers from the continuous variables qc logic.
