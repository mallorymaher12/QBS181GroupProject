# QBS181GroupProject
Mallory, Libby, Sean, Emma, and Carson

Introduction:	
Mental health disorders have - and continue to - become increasingly problematic in society, and with new technologies and social media platforms the issue is only worsening. Depression and anxiety are the most common mental health disorders especially among adolescents and young adults. We often see these disorders occur in conjunction with eating disorders as well as alcohol and drug use. According to the NIH, young adults aged 18-25 years had the highest prevalence of any mental illness, or AMI, (29.4%) compared to adults aged 26-49 years (25.0%) and aged 50 and older (14.1%) in the year 2019 [2]. However, only 38.9% of young adults with AMI received any sort of mental health service that year [2].
Given the rise in prevalence of mental health disorders it is important to understand how that measure has changed over time and what groups of society have been affected. For example, cultural differences affect risk factors for developing mental health disorders. Therefore, prevalence likely differs across countries and it is important to understand what parts of the world are most affected by mental health disorders. Likewise, we want to understand what age groups and sexes might be more affected than others so that we can appropriately target them for treatment and other interventions. 

Data Description:				
This dataset provides measures of prevalence of depression, anxiety, and other mental health and substance abuse disorders, across countries and years. This will allow us to easily compare the prevalence of depression across countries and analyze how it has changed over time. One of the things that we liked about this data set is that there are six different data sets, giving us valuable practice in joining tables and learning how to investigate several tables that originally were not in the same datasheet. 
Some of the data stretches from 1800 up until 2017, but we will be focusing on 1990 to 2017 since that is the common time period that all countries have (some countries don’t have data prior to 1990). The other datasets have measures of prevalence for depression based on education level, sex, and age. This data will allow us to compare the measurements within these various groups. It is also indexed by country and age, so we can further analyze how subgroups differ across countries and how prevalence has changed over time within them.

Datasets:
Prevalence by Mental and Substance: Describes the prevalence of various mental and substance abuse disorders by country and year
Number of observations: 6468
Columns: Entity (string), Code (string), Year (Date), Schizophrenia (integer), Bipolar Disorder (integer), Eating Disorders (integer), Anxiety Disorders (integer), Drug Use Disorders (integer), Depression (integer), Alcohol Use Disorders (integer)
Depression by Level of Education: Describes the prevalence of depression across different levels of education by country in the year 2014
Number of observations: 26
Columns: Entity (string), Code (string), Year (Date), all_levels_active (integer), all_levels_employed (integer), all_levels_total (integer), below_upper_secondary_active (integer), below_upper_secondary_employed (integer), below_upper_secondary_total (integer), tertiary_active (integer), tertiary_employed (integer), tertiary_total (integer), upper_secondary_post_secondary_non_tertiary_active (integer), upper_secondary_post_secondary_non_tertiary_employed (integer), upper_secondary_post_secondary_non_tertiary_total (integer)
Prevalence of Depression by Age: Describes the prevalence of depression across age groups by country and year
Number of observations: 6468
Columns: Entity (string), Code (string), Year (Date), all ages (integer), 10-14 (integer), 15-19 (integer), 20-24 (integer), 25-29 (integer), 30-34 (integer), 15-49 (integer), 50-69 (integer), 70+ (integer)
Prevalence of Depression Males: Describes the prevalence of depression in males and females and has total population by year and country
Number of observations: 47,807
Columns: Entity (string), Code (string), Year (string), prevalence in males (integer), prevalence in females (integer), population (integer)
Number with Depression by Count: Describes the total number of people living with depression (both males and females and all ages) by year and country
Number of observations: 6468
Columns: Entity (string), Code (string), Year (Date), prevalence of depressive disorders both sexes and all ages (integer)

Aim 1: Graphical Representation of Prevalence of Depression		
1.1. Create a graphical representation of the geographical distribution of mental health 	concerns across countries
1.2. Create a graphical representation of international mental health distribution stratified 	by various demographic characteristics (age, sex, etc.)

Aim 2: Analytic Model of Mental Health		
2.1. Construct regression models that predict prevalence of depression using variables in the datasets such as sex, education, and age 


Concluding Remarks:
In sum, we aim to provide graphic representations of the geographic distribution of mental health problems, both as crude rates and rates stratified by various demographic characteristics. We may also aim to provide an adjusted crude representation to account for varying demographic characteristics of the countries in question. Finally, we plan to numerically account for the differential geographic distribution of mental health via an exploratory regression analysis. As outlined above, this data will be largely from 1990 onwards, which we will extract from our larger linked datasets. Our tentative working plan will be to review data in Excel, sort our data in SQL, and perform statistical analyses in R and graphical analyses in R or Tableau. We hope that our wrangling and analysis of this dataset will elucidate some insight into international trends in mental health problems. 
