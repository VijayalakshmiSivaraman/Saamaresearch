# Saamaresearch
##  Pyhack2021
## Problem summary
Data from Clinical Trials are collected by the means of various Forms. For example, in this Hackathon, we have the Adverse Event (AE) and Concomitant Medication (CM) Forms and their respective information collected. The Adverse Event (AE) Form captures all the adverse side effects the Patient or Subject may face during a Clinical Trial after enrollment. These effects can then be treated by a medication, called Concomitant Medication and the related data is again captured as a Concomitant Medication (CM) Form. Hence we can see that both Adverse Events (AE) and Concomitant Medications (CM) are interrelated. Here, we will provide two datasets, each of AE and CM Forms samples as CSV files, to access full dataset use the APIs. APIs must be called after referring to the API guide and the goal of this Hackathon is to find specific issues with this data.
## Solution
Got a list of subjectids for the given study id + domain id

Got subject data for study id + domain id + subject id

Processed data to find discrepancy (diffent type of discrepancies are defined above)
### Note: certain dates were invalid in ae and cm subject data
