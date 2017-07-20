---
title: Measles models
---

**Model name:** Measles model  
**Modellers:** [Matthew Ferrari](http://bio.psu.edu/directory/mjf283), [Kirsten Eilertson](http://stat.psu.edu/people/kee12)   
**Institution:** [Pennsylvania State University](http://www.psu.edu/)

A state-space statistical framework is used to fit a dynamic transmission model to historical measles case surveillance data from each country.  The result is a stochastic, age-specific model of measles transmission with country-specific parameter estimates for transmission rate and strength of herd immunity.  Forward projections of measles burden incorporate both stochasticity in transmission dynamics and bootstrap draws from confidence intervals for estimated parameters.    

---   

<div id="LSHTM"></div>

**Model name:** DynaMICE (Measles model)    
**Modellers:** [Mark Jit](http://www.lshtm.ac.uk/aboutus/people/jit.mark), [Stéphane Verguet](https://www.hsph.harvard.edu/stephane-verguet/)    
**Institution:** [London School of Hygiene & Tropical Medicine (LSHTM)](http://www.lshtm.ac.uk/)

DynaMICE (Dynamic Measles Immunisation Calculation Engine) is a compartmental dynamic model of measles transmission and disease. It was developed by investigators at the London School of Hygiene & Tropical Medicine, Harvard University and the University of Montreal, initially with WHO funding to inform the impact of measles SIAs. It has now been expanded to consider the impact of routine first and second dose as well as Supplementary Immunisation Activities (SIAs) in all Decade of Vaccines countries under a variety of schedules.

The model is an age-structured SIRV (Susceptible-Infectious-Recovered-Vaccinated) model that uses [POLYMOD](https://ec.europa.eu/research/fp6/ssp/polymod_en.htm) contact matrixes to inform transmission between age groups to estimate measles cases. Uses external country specific parameters of population, R0, vaccine coverage & case fatality rate to estimate total numbers of cases and deaths. Parameters such as vaccine efficacy are age stratified with differing efficacies below and above age one. Recent modification of the model is to incorporate vaccine timeliness by modelling the first three years on weekly time steps to simulate fine scale vaccine deployment data.

[![](/img/models/dynemice.png)](/img/models/dynemice.png)

> Predictions of measles incidence pre- and post-SIA in India, under different assumptions about the interval between SIAs. From: Verguet et al. [Controlling measles using supplemental immunization activities: A mathematical model to inform optimal policy. (2015)](http://www.sciencedirect.com/science/article/pii/S0264410X14016077)

---

[More about measles](/diseases/measles)  
[Relevant publications](/publications#measles)
