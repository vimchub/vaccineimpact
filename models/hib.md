---
title: Hib, rotavirus, and pneumococcal models
---

**Model name:** UNIVAC (Hib, rotavirus and pneumo model)    
**Modellers:**  [Andrew Clark](http://www.lshtm.ac.uk/aboutus/people/clark.andrew), [Colin Sanderson](http://www.lshtm.ac.uk/aboutus/people/sanderson.colin), [Petra Klepac](http://www.petraklepac.com/Site/Home.html), [Kaja Abbas](https://www.lshtm.ac.uk/aboutus/people/abbas.kaja), and Hira Tanvir      
**Institution:** [London School of Hygiene and Tropical Medicine (LSHTM)](http://www.lshtm.ac.uk/)

UNIVAC is a static cohort model now based in R (and previously based in Excel). The model was originally developed to provide national ministries of health in low and middle income countries with conservative estimates of the impact and cost-effectiveness of routine Hib, rotavirus and pneumococcal vaccination. UNIVAC has also been used to provide Gavi with conservative estimates of the number of cases, deaths and Disability-Adjusted Life Years (DALYs) prevented by these vaccines over the period 2001-2030 in countries involved in WHO’s Global Vaccine Action Plan (GVAP).  

The model tracks 30 stacked/successive cohorts from birth until death. Demographics are taken from the United Nations Population Division. Estimates of disease incidence and mortality are based on CHERG/MCEE estimates (Child Health Epidemiology Reference Group / Maternal Child Epidemiology Estimation). Disease age distributions are based on the literature and surveillance. Estimates of dose-specific coverage and vaccine timeliness are based on [WUENIC](https://apps.who.int/immunization_monitoring/globalsummary/timeseries/tswucoveragedtp3.html), [DHS](http://dhsprogram.com/) and [MICS](http://mics.unicef.org/) data. Dose-specific vaccine efficacy and duration of protection assumptions are based on Cochrane/SAGE reports.    

> Clark, Andrew; Tate, Jacqueline; Parashar, Umesh; Jit, Mark; Hasso-Agopsowicz, Mateusz; Henschke, Nicholas; Lopman, Benjamin; Van Zandvoort, Kevin; Pecenka, Clint; Fine, Paul; +1 more... (2019) [Mortality reduction benefits and intussusception risks of rotavirus vaccination in 135 low-income and middle-income countries: a modelling analysis of current and alternative schedules.](https://researchonline.lshtm.ac.uk/id/eprint/4654812/) The Lancet Global Health, 7 (11). e1541-e1552.

> Clark, A., Jauregui, B., Griffiths, U., Janusz, C.B., Bolaños-Sierra, B., Hajjeh, R., Andrus, J.K. and Sanderson, C. (2013). [TRIVAC decision-support model for evaluating the cost-effectiveness of Haemophilus influenzae type b, pneumococcal and rotavirus vaccination](https://doi.org/10.1016/j.vaccine.2013.05.045) Vaccine 31 Suppl 3, pp. C19-29. 

> Atchison C, Lopman B, Edmunds WJ. [Modelling the seasonality of rotavirus disease and the impact of vaccination in England and Wales.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7021296/) Vaccine. 2010 Apr 19;28(18):3118-26. doi: 10.1016/j.vaccine.2010.02.060. Epub 2010 Mar 1. PubMed PMID: 20197142.

> Pitzer VE, Atkins KE, de Blasio BF, Van Effelterre T, Atchison CJ, Harris JP, Shim E, Galvani AP, Edmunds WJ, Viboud C, Patel MM, Grenfell BT, Parashar UD, Lopman BA. [Direct and indirect effects of rotavirus vaccination: comparing predictions from transmission dynamic models.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0042320) PLoS One. 2012;7(8):e42320. doi: 10.1371/journal.pone.0042320. Epub 2012 Aug 13. PubMed PMID: 22912699; PubMed Central PMCID: PMC3418263.

---      

<div id="jhu"></div>

**Model name:** [Lives Saved Tool (LiST) (Hib, rotavirus and pneumo model)](http://www.livessavedtool.org/)   
**Modellers:**  [Neff Walker](https://www.jhsph.edu/faculty/directory/profile/1945/neff-walker), [Yvonne Tam](https://www.jhsph.edu/faculty/directory/profile/2424/yvonne-yin-on-tam), and [Emily Carter](https://www.jhsph.edu/faculty/directory/profile/3517/emily-d-carter)    
**Institution:** [Johns Hopkins Bloomberg School of Public Health](https://www.jhsph.edu/)

The Lives Saved Tool (LiST), developed by the Institute for International Programs at Johns Hopkins Bloomberg School of Public Health and funded by the Bill & Melinda Gates Foundation, is a multi-cause model that estimates the impact of scaling up more than 70 evidence-based  health and nutrition interventions, including vaccines, on maternal mortality, neonatal mortality, child mortality, and stillbirths. 

LiST has been characterized as a linear, mathematical model that is deterministic. LiST is a module in Spectrum, a software package maintained by Avenir Health, with links to the demography module (DemProj), AIDS impact module (AIM), and the family planning module (FamPlan). LiST has been used for over 10 years and is regularly updated to incorporate the latest evidence from the scientific literature and household survey data. LiST is free and publicly available for use.

[![](/img/models/hib_pneumo_rota_model.jpg)](/img/models/hib_pneumo_rota_model.jpg)

> LiST model structure visualisation

> Walker, N., Tam, Y., Friberg, I.K. (2013) [Overview of the Lives Saved Tool (LiST)](https://bmcpublichealth.biomedcentral.com/track/pdf/10.1186/1471-2458-13-S3-S1) BMC Public Health volume 13, Article number: S1 (2013)

---

<div id="Emory"></div>


**Model name:** Emory Rotavirus Vaccine Model   
**Modellers:** [Ben Lopman](https://www.sph.emory.edu/faculty/profile/#!BLOPMAN) and [Alicia Kraay](https://www.blopman.net/ourteam)       
**Institution:** [Emory University Rollins School of Public Health](https://www.sph.emory.edu/index.html)

The Emory Rotavirus Vaccine Model uses a deterministic, age-structured compartmental model of rotavirus transmission and disease. The model follows a Susceptible–Infected–Recovered-Susceptible (SIRS) structure, with complexity added to capture rotavirus natural history. Infants are born into the model with maternal immunity. As maternal immunity wanes, infants become susceptible to a primary rotavirus infection, which has a certain probability of causing rotavirus gastroenteritis.  

The model assumes previous infection confers protection against both subsequent rotavirus infections and disease. Primary infections are assumed to be more infectiousness than subsequent ones. The model assumes primary, secondary and tertiary infections have different probabilities for developing gastroenteritis for the probability that that disease is severe. It assumes that only severe rotavirus gastroenteritis cases progress to death. It assumes that vaccine-induced immunity is similar to natural immunity. Values and ranges for natural history parameters are informed by cohort and challenge studies.

---



More about [Hib](/diseases/hib), [rotavirus](/diseases/rotavirus) and [pneumococcal disease](/diseases/pneumo)  
[Relevant publications](/publications#hib)
