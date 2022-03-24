# DAS2022-Group-10
# Influential Factors of the Number of Days an Animal Spends at the Shelter

This is a group project of the course "Data Analysis Skills" finished by Hanfan Chen, Zhaohao Li, Zhenhao Qiao, Chao Wang, Rachael Watson at the University of Glasgow.

Dataset 10 comes from the Dallas animal shelter. The dataset contains a variety of information relating to each animal admitted to the shelter. 
• Animal_type – The type of animal admitted to the shelter
• Month – Month the animal was admitted, recorded numerically with January=1
• Year – Year the animal was admitted to the shelter
• Intake_type – Reason for the animal being admitted to the shelter
• Outcome_type – Final outcome for the admitted animal
• Chip_Status – Did the animal have a microchip with owner information?
• Time_at_Shelter – Days spent at the shelter between being admitted and the final outcome

This report tries to investigate which of these factors are influential in determining the number of days an animal spends at the shelter before its final outcome is decided by generalised linear models. Since the response variable is a count data, we fit a Poisson at the first stage and check if it is suitable. Since the fitness is not good, we select the Binomial-Negative Binomial model as the final model decision.
