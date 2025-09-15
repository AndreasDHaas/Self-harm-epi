**Description**

This study aims to examine the incidence and prognostic factors of intentional self-harm events and subsequent mortality from unnatural causes among beneficiaries of a private medical insurance scheme. 


**Objectives**

1. Estimate the incidence of intentional self-harm events.
2. Investigate the prognostic factors of intentional self-harm events.
3. Examine the incidence of mortality from unnatural causes among individuals with and without history of self-harm.
4. Evaluate intentional self-harm as a predictor of mortality from unnatural causes.


**Data**

We analysed national vital registration data along with longitudinal inpatient and outpatient reimbursement claims data from a South African general medical insurance scheme and a South African HIV disease management program. 
Included are individuals aged 10 years or older who were covered by the medical insurance scheme at any time between 1 January 2011 and 30 June 2020, or those enrolled in the HIV disease management program at any time 
between 1 January 2011 to 1 October 2022. Individuals with unknown sex or age are excluded from the analysis. Those with an unconfirmed vital status who could not be linked to the vital registration system, are excluded from the mortality analysis.


Raw data were merged and cleaned in *Stata* by Andreas Haas (andreas.haas@unibe.ch), and organized into several datasets that are ready to be used for the analyses: 

- analyseWide: wide table with demographics, start and end of follow-up, comorbidities, and mortality

  - uncensored mortality: death_d_orig, death_y_orig, cod1_orig, cod2_orig 
  - mortality after end of insurance coverage censored: death_d, death_y, cod1, cod2 
  
  <br>
  
- eventsLong: long table with all self-harm events and events of undetermined intent

- episodesLong7: long table with self-harm events and events of undetermined intent grouped into episodes: 
  - claims that occurred within 7 days from the initial event (claim) were combined into treatment episodes assuming they relate to the same event.
 
*All datasets were saved in Stata format (dta) version 12.*
