# Toxoplasmosis-at-AIDS-diagnosis
## Background
The file `aidsQuebec1979-1994.RData` contains de-identified information about individual diagnoses (Dx) of Acquired Immunodeficiency Syndrome (AIDS) among adults ≥15 years of age in Québec between 1979, when the first case was identified, and 1994. Amongst the information is date of diagnosis, expressed in years with decimals (`DxDate`); the age of the individual at diagnosis (`DxAge`); the risk category of the individual as it was recorded at the time (`RiskCat`); and an indicator for toxoplasmosis as a diagnostic disease for AIDS. These diagnostic diseases, numbering 23 at the time, were used to identify the individual as having AIDS after a period of HIV seropositivity.

The risk category is specified as follows:

**MSM**: Men who have sex with men (MSM)

**IDU**: Injection drug users (IDU)

**MSM/IDU**: Both MSM and IDU

**HEM**: People with haemophilia

**HPR**: People with a heterosexual partner at risk

**HEC**: People from HIV-endemic countries

**TRN**: People infected through transfusion

Among the diagnostic diseases of AIDS is toxoplasmosis (indicator TOXO), caused by a common microscopic parasite, which is usually asymptomatic in people with uncompromised immune systems. In AIDS patients, however, it can cause severe symptoms, including confusion, seizures, inflammation of the retina and a pneumonia-like lung condition. We consider the effect of age separately in each risk category (through an interaction) on the probability of toxoplasmosis, adjusting for the number of years since the first AIDS diagnosis in Québec.

We aim to fit appropriate generalised multivariable linear model by maximum likelihood and point estimates and 95% confidence intervals for the **odds ratio**, the **relative risk** and the **risk difference** for the following comparisons:

a. between the ages of **30** and **50** among people with AIDS from **HIV-endemic countries**

b. between people with **AIDS from HIV-endemic countries** and **people with AIDS with a heterosexual partner** at risk at the age of **30**.
