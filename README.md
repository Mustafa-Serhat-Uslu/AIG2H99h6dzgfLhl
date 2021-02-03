# x9tvI8VTYwrdgCvo


# Mustafa Serhat USLU -- Tel: 0 553 524 27 50 -- uslu.mserhat2@gmail.com

# RESULTS:
#          (Go To the Very Bottom of the Report for Quick View of the Results)
#
#          - 0.94 Average Accuracy with similar F1 values achieved by Random Forest Algorithm 
#          - 0.88 Average Accuracy with similar F1 values achieved by Desicion Tree Algorithm
#          - 0.87 Average Accuracy with similar F1 values achieved by K-NN 

# BONUS:
#        >>> According to the Categorical Feature Analysis:
#             - Students have the highest chance of subscribing (15%), housemaids have the lowest chance (4%)  [at box 21]
#             - Single and Divorced people have a higher chance of subscribing opposed to Married people       [at box 22]
#             - Education level and subscribtion chance have a positive correlation                            [at box 23]
#             - People who hasn't defauled have a slightly higher chance of subscribing                        [at box 24]
#             - Housing and subscribtion has a negative correlation                                            [at box 25]
#             - Loans and subscribtion has a negative correlation                                              [at box 26]
#             - People who has been contacted by a cellular phone has a higher chance of suscribing            [at box 27]
#
#        >>> According to the Numerical Feature Analysis:
#             - Age > Balance == Duration > Num_ofPeople_in_Campaign is the order of features having higher correlation with "y"

# SUMMARY:
#        *Pre-Processing:
#             -> checked nulls
#             -> dtypes checked 
#             -> Processed Numerical Features
#                  -"y"        1-One Hot Encoding
#                  - "age"      1-outlier analysis 2-standardize 
#                  - "balance   1-outlier analysis 2-standardize
#                  - "day"      1-REMOVE
#                  - "duration  1-outlier analysis 2-standardize
#                  - "campaign" 1-produce "Num_of_ppl_in_campaign" then remove "campaign" 2-standardize
#             -> Processed Categorical Features
#                  - "job"         1-ONE HOT ENCODE         
#                  - "marital"     1-ONE HOT ENCODE
#                  - "education"   1-ONE HOT ENCODE
#                  - "default"     1-ONE HOT ENCODE
#                  - "housing"     1-ONE HOT ENCODE
#                  - "loan"        1-ONE HOT ENCODE
#                  - "contact"     1-ONE HOT ENCODE
#                  - "month"       1-REMOVE
#       
#          *Over-Sampling the yes instances with SMOTE
#           
#          *5-Fold Cross-Validation Split
#
#          *Predictions and Evaluations
