# Medical_Turnout_Appointment_Analysis

#### In this project, I analysed dataset of more than 110k Brazilian patients from late April to early June 2016. Data shows that in 20% of scheduled appointments, the patient didn't show up. My goal was trying to answer the question:
##### what are the factors leading to no_shows?
##### Is it the system or personal attributes to blame?

The report distinguishes between two groups of factors that might have significance: those related to the system, and personal attributes of the patients themselves.

### Results
>This report examined a dataset of Brazilian patients, trying to figure out what are the factors that correlates with missing appointments.

>It found that the most important factor was whether the patient got his appointment at the same day of booking. This factor was negatively correlated with no_show cases, meaning that there were less no_shows when the patient was scheduled on the same day.

>Regarding the system, the report found that sending SMS notifications didn't help. In fact, it was weakly positively correlated with no_show cases. Implying that those who received an SMS were slightly more likely to miss. Receiving benefits from Bolsa Família didn't seem to correlate with no_show cases.

>Personal attributes didn't seem to correlate with no_shows. Except that patients who missed their appointments were younger in general of those who didn't. It is also noted that having multiple illnesses seems to correlate with less no_shows.

### Limitations
>Most columns in the dataset are binary variables (categorical variables that take only two values), including the dependent variable noshow. This limits the statistical methods that can be used to analyze the data.

>Some results were counter-intuitive, The analysis found that there is a slight higher chance of no_show for those who received an SMS. The nature of the data prevents further investigation.

>It's important to note that this analysis focus is on the correlation between the variables. This is not enough to assume there is a causal relation between them. Further studies using inferential statistics is required for that. Also, most correlations were weak due to the categorical nature of the variables.
