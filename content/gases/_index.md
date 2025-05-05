---
description: 'Blood gases app'
featured_image: "/images/abg.png"
title: Gases
---

<div class=RWH_left>

Here is an [interactive educational app](https://kidneyfish.shinyapps.io/davenport_plot/) for interpreting blood gases.  


## Terms

- `aHCO3>` = actual bicarbonate = what the bicarbonate concentration is in the sample  
- `stdHCO3` = what the bicarbonate concentration would have been if PaCO<sub>2</sub> was normal (i.e. under standard conditions: T37, fully oxygenated, PaCO<sub>2</sub> 5.3 kPa)  
- `BE` = base excess = the amount of strong acid that must be added to each liter of fully oxygenated blood to return the pH to 7.40 under standard conditions  

<br>

Therefore, stdHCO<sub>3</sub> and BE report the metabolic component of any disturbance, accounting for the interconversion of CO<sub>2</sub> and HCO<sub>3</sub>.  

<br>

## Plots

The relationship between pH, PaCO<sub>2</sub> and HCO<sub>3</sub> is described by the Henderson-Hasselbalch equation and can be plotted in three dimensions:

![](/images/nomogram_3D.png)

There are two methods used to project this on to two demensions.   Horace Davenport (c. 1958, after van Slyke), plotted pH vs. HCO<sub>3</sub> with PaCO<sub>2</sub> isopleths.  Siggaard-Andersen (Copenhagen, 1971) preferred plotting pH vs. PaCO<sub>2</sub> with BE lines.  

<br>

## Compensation

The compensation lines for Davenport plots are drawn according to the following "Boston Rules" (Schwartz & Relman, NEJM 1963; Berend et al., NEJM 2014):  

- acute respiratory acidosis: 1 mM rise in HCO<sub>3</sub> per 10 mmHg rise in PaCO<sub>2</sub>  
- acute respiratory alkalosis: 2 mM fall ditto  
- chronic respiratory acidosis: 4 mM rise in HCO<sub>3</sub> per 10 mmHg rise in PaCO<sub>2</sub>  
- chronic respiratory alkalosis: 5 mM fall ditto  
- metabolic acidosis: PaCO<sub>2</sub> = 1.5 * HCO<sub>3</sub> + 8 = 'Winter's formuala' (Dell & Winters, 1967)  
- metabolic alkalosis: PaCO<sub>2</sub> = 0.7 * HCO<sub>3</sub> + 20  

<br>

For acute respiratory disturbances, compensation lines extended approximately along the dashed 'van Slyke buffer line'.  

<br>

The compensation lines for Siggaard-Andersen plots are drawn according to the following [Severinghaus](https://pubmed.ncbi.nlm.nih.gov/9671365/) rules:  

- acute respiratory disturbance: no change in BE
- chronic respiratory disturbance: BE changes by 0.4 * PaCO<sub>2</sub> 
- metabolic acidosis: PaCO<sub>2</sub> changes by 1 * BE
- metabolic alkalosis: PaCO<sub>2</sub> changes by 0.6 * BE

<br>

Due to uncertainty around the accuracy of these rules, the lines are deliberately drawn without confidence intervals.  (However, these are probably in the range of [+/- 5 mM](https://pubmed-ncbi-nlm-nih-gov.eux.idm.oclc.org/18308967/) for bicarbonate response to respiratory perturbations.)  There are limits to the extent to which compensation can occur, so the compensation curves are likely to flatten off at extremes (not shown on the app).  For example, requirement for O<sub>2</sub> exchange may limit the extent to which ventilation rate can be lowered to compensate for a metabolic alkalosis.  

</div>

