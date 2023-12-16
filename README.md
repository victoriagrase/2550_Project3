## Modeling Cardiovascular Disease Risk: Evaluating Predictive Performance in the NHANES Target Population Using Framingham Heart Study Data

## Abstract
This study aimed to compare simulation and data-based analysis for transportability purposes, assessing the
efficacy of both approaches in generalizing findings from target populations to larger and more expansive
populations who meet certain criteria. The goal was to evaluate how insights derived from simulation
and empirical data analysis contribute to the transportability of results, particularly when extrapolating
conclusions to broader segments of the overall population. Professionals in the healthcare system often rely
on these multivariable risk algorithms to estimate the likelihood of specific CVD events in a target population.
This investigation utilized data from the Framingham Heart Study through the risk Communicator package
to construct a prediction model for assessing the risk of cardiovascular disease (CVD) events. Subsequently,
it evaluated the model’s performance in a target population derived from the National Health and Nutrition
Examination Survey (NHANES) data using the nhanesA package. The logistic regression method was
employed to assess the probability of CVD event occurrence in a binary setting within the NHANES target
population, comprising 2,838 study participants. The study population, with a mean age of 46.65 years
and 1,512 women, consisted of individuals who underwent routine examinations between 30 and 62 years
of age and were free of any prior stroke or heart occurrences. The sex-specific multivariable risk functions,
often referred to as “general CVD” algorithms, incorporated variables such as age, total and high-density
lipoprotein cholesterol, systolic and diastolic blood pressure, treatment for hypertension, smoking status, body
mass index (BMI), blood pressure medication usage, and diabetes status.The study aimed to comprehensively
assess the predictive performance of the model within the NHANES target population. The findings and
results of this evaluation show the Monte Carlo simulation, with a high-density cluster around the test Brier
estimate is much higher than the brier score in the target NHANES population (0.047) and lower densities
for brier estimates beyond 0.20, indicates a degree of variability in the model that is unaccounted for.

## References and Acknowledgements
1. ”Transporting a prediction model for use in a new target population” (Jon A. Steingrimsson, Constantine
Gatsonis, and Issa J. Dahabreh)-2021

2. ”General Cardiovascular Risk Profile for Use in Primary Care-The Framingham Heart Study” (Ralph B.
D’Agostino, Sr, PhD, Ramachandran S. Vasan, MD, Michael J. Pencina, PhD, Philip A. Wolf, MD, Mark
Cobain, PhD, Joseph M. Massaro, PhD, and William B. Kannel, MD)-2008

4. Li, Bing & Gatsonis, Constantine & Dahabreh, Issa & Steingrimsson, Jon. (2022). Estimating the area
under the ROC curve when transporting a prediction model to a target population. Biometrics. 79.
10.1111/biom.13796.

This project is a collaboration with Dr. Jon Steingrimsson from the Department Biostatistics. This project is advised by Dr. Alice Paul (alice_paul@brown.edu)
