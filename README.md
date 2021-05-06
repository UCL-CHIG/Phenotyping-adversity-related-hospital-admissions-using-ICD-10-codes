# Phenotyping-adversity-related-hospital-admissions-using-ICD-10-codes
This repository covers ICD-10 codes from 3 mutually non-exclusive code lists which can be used to identify admissions related to substance misuse, mental health problems, or exposure to violence in hospital records in England. We also include basic R code which we used to identify women with a history of adversity-related hospital admissions prior to birth using a three-year look-back window in the Hospital Episode Statistics data.

The codes were used in the following piece of work:
Pearson, R., Jay, M. A., Wijlaars, L., De Stavola, B., Syed, S., Bedston, S., Gilbert, R. (2020). Association between health indicators of maternal adversity and the rate of infant entry to local authority care in England: a longitudinal ecological study. BMJ Open https://doi.org/10.1136/bmjopen-2019-036564

# 

These codes come from several published ICD-10 code lists:

## 1) Substance misuse:
Alcohol misuse\
E51.2, T51.0, X45.0-X45.2, X45.4, X45.6, X45.8, X45.9, X65.0-X65.2, X65.4, X65.5, X65.6, X65.8, X65.9, Y15.0, Y15.2, Y15.4, Y15.8, Y15.9, Y90.0-Y91.3, Y91.9, Z50.2, Z71.4, Z72.1

*For further details see: [Fone D, Morgan J, Fry R, et al. Change in alcohol outlet density and alcohol-related harm to population health (CHALICE): a comprehensive record-linked database study in Wales. Public Heal Res Published Online First: 2016.](http://dx.doi.org/10.3310/phr04030)*

Alcohol and other substance misuse\
E24.4, F10-F16, F18-F19, G31.2, G62.1, G72.1, I42.6, K29.2, K70.0-K70.9, K85.2, K86.0, O35.4, R78.0-R78.5, T36-T50 (we did not exclude T50.6, however), X40-X44, X46-X49, X69, Y10-Y14, Y16-Y19, Z04.0, Z50.3, Z71.5, Z72.2, T51

*For further details see: [Herbert A, Gilbert R, González-Izquierdo A, et al. Violence, self-harm and drug or alcohol misuse in adolescents admitted to hospitals in england for injury: A retrospective cohort study. BMJ Open 2015;5.](http://dx.doi.org/10.1136/bmjopen-2014-006079)*

## 2) Exposure to violence:
Assault\
X85-X99, Y01-Y05, Y08-Y09

Maltreatment\
T73-T74, Y06-Y07

Injury: undetermined cause\
Y20-Y34, Z04.5 (we excluded Z04.8 - Examination and observation for other specified reasons)

*For further details see: [Herbert A, Gilbert R, González-Izquierdo A, et al. Violence, self-harm and drug or alcohol misuse in adolescents admitted to hospitals in england for injury: A retrospective cohort study. BMJ Open 2015;5.](http://dx.doi.org/10.1136/bmjopen-2014-006079)*

## 3) Mental Health disorders:
Behavioural and emotional disorder\
F90-F95, F98

Neurotic, stress-related, and somatoform disorder\
F40-F45, F48

Schizophrenia , Personality disorder, or Bipolar disorder\
F20, F30-F33, F60-F62 

Depressive episode or disorder\
F32-F33

Substance use disorder\
F10-F16, F18-F19

Other mental health disorder\
F00-F09, F21-F25, F28, F34, F38-F39, F50-F55, F59, F63-F66, F68-F73, F79-F84, F88-F89, F99

*For further details see: [Nilsson SF, Laursen TM, Hjorthøj C, et al. Risk of psychiatric disorders in offspring of parents with a history of homelessness during childhood and adolescence in Denmark: a nationwide, register-based, cohort study. Lancet Public Heal 2017;2:E541–50.](https://doi.org/10.1016/S2468-2667(17)30210-4)*

Intentional self-harm\
X60-X84

History of self-harm\
Z91.5 (we also included Y87.0 – sequelae of intentional self-harm)

*For further details see: [Herbert A, Gilbert R, González-Izquierdo A, et al. Violence, self-harm and drug or alcohol misuse in adolescents admitted to hospitals in england for injury: A retrospective cohort study. BMJ Open 2015;5.](http://dx.doi.org/10.1136/bmjopen-2014-006079)*

## 

These code lists were informed by searches undertaken by Shabeer Syed as part of separate piece of work

*For further details see: [Syed S, Ashwick R, Schlosser M, et al. Predictive value of indicators for identifying child maltreatment and intimate partner violence in coded electronic health records: a systematic review and meta-analysisArchives of Disease in Childhood 2021;106:44-53.](http://dx.doi.org/10.1136/archdischild-2020-319027)*

