---
title: Measles models
---

**Model name:** Measles model  
**Modellers:** [Matthew Ferrari](http://bio.psu.edu/directory/mjf283) and [Kirsten Eilertson](http://stat.psu.edu/people/kee12)   
**Institution:** [Pennsylvania State University](http://www.psu.edu/)

This is a stochastic, age-specific, phenomenological transmission model that is fit independently to each country based on annual cases reported to WHO. Herd effects are represented in an annualized attack rate function that assumes reduced transmission as population immunity increases. Model parameters (attack rate function and observation rates) are updated annually based on new reported cases in collaboration with WHO. Model projections reflect stochastic variation in transmission and confidence intervals on estimated parameters.  

> Chen. S, Fricks J, Ferrari M.J. [Tracking measles infection through non‐linear state space models](https://doi.org/10.1111/j.1467-9876.2011.01001.x) Journal of the Royal Statistical Society Volume61, Issue 1, January 2012 Pages 117-134

---   

<div id="LSHTM"></div>

**Model name:** DynaMICE (Measles model)    
**Modellers:** [Mark Jit](http://www.lshtm.ac.uk/aboutus/people/jit.mark), [Stéphane Verguet](https://www.hsph.harvard.edu/stephane-verguet/), [Petra Klepac](https://www.lshtm.ac.uk/aboutus/people/klepac.petra), [Kaja Abbas](https://www.lshtm.ac.uk/aboutus/people/abbas.kaja), [Kiesha Prem](https://www.lshtm.ac.uk/aboutus/people/prem.kiesha), and [Han Fu](https://www.lshtm.ac.uk/aboutus/people/fu.han)       
**Institution:** [London School of Hygiene & Tropical Medicine (LSHTM)](http://www.lshtm.ac.uk/)

DynaMICE (Dynamic Measles Immunisation Calculation Engine) is a compartmental dynamic model of measles transmission and disease. It was developed by investigators at the London School of Hygiene & Tropical Medicine, Harvard University and the University of Montreal, initially with WHO funding to inform the impact of measles SIAs. It has now been expanded to consider the impact of routine first and second dose as well as Supplementary Immunisation Activities (SIAs) in all Decade of Vaccines countries under a variety of schedules.

The model is an age-structured SIRV (Susceptible-Infectious-Recovered-Vaccinated) model that uses [POLYMOD](https://ec.europa.eu/research/fp6/ssp/polymod_en.htm) contact matrixes to inform transmission between age groups to estimate measles cases. Uses external country specific parameters of population, R0, vaccine coverage & case fatality rate to estimate total numbers of cases and deaths. Parameters such as vaccine efficacy are age stratified with differing efficacies below and above age one. Recent modification of the model is to incorporate vaccine timeliness by modelling the first three years on weekly time steps to simulate fine scale vaccine deployment data.

[![](/img/models/dynemice.png)](/img/models/dynemice.png)

> Predictions of measles incidence pre- and post-SIA in India, under different assumptions about the interval between SIAs. 

> From: Verguet et al. [Controlling measles using supplemental immunization activities: A mathematical model to inform optimal policy. (2015)](http://www.sciencedirect.com/science/article/pii/S0264410X14016077) Vaccine. 33 (10), 1291-1296. Licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives License](https://creativecommons.org/licenses/by-nc-nd/4.0/)    

---

[More about measles](/diseases/measles)  
[Relevant publications](/publications#measles)
