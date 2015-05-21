#Evidence.target2drug.association_score

This score represents the level of confidence in assignment of the therapeutic target of the drug:
* Score = 1, if therapeutic target has been manually curated from literature and drug package inserts


#Evidence.drug2clinic.association_score

These scores reflect the probability of a drug being approved for a given indication given that it reaches a particular clinical phase. These have been assigned on the basis of:
* Score = 1, if the clinical indication for a given drug has been extracted either from the DailyMed package insert or the ATC classification, or from a clinical trial in phase 4 in ClinicalTrials.gov
* Score = 0.7, if the clinical indication for a given drug has been extracted from ClinicalTrials.gov and the highest phase for that drug and clinical indication is phase 3 
* Score = 0.2, if the clinical indication for a given drug has been extracted from ClinicalTrials.gov and the highest phase for that drug and clinical indication is phase 2
* Score = 0.1, if the clinical indication for a given drug has been extracted from ClinicalTrials.gov and the highest phase for that drug and clinical indication is phase 1
* Score = 0.09, if the clinical indication for a given drug has been extracted from ClinicalTrials.gov and the highest phase for that drug and clinical indication is phase 0
