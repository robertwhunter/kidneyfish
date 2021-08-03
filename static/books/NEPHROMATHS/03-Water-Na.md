# Water and sodium

Na^+^ is the dominant extracellular cation and, as such, its concentration depends on the total body stores of water and exchangeable ions.  Na^+^ and K^+^ are the most abundant cations (and will be accompanied by anions to maintain electroneutrality), thus:

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">The Edelman equation:  
\begin{equation}
  P_{Na} = \frac{Na_{e} + K_{e}}{TBW}
  (\#eq:edelman)
\end{equation}

...where Na~(e)~ and K~(e)~ are exchangeable sodium and potassium and TBW is total body water.  For an elegant discussion of the derivation of this equation see [@rose1986].
</div>\EndKnitrBlock{eqnpanel}

Any abnormality in plasma sodium concentration (P~Na~) usually reflects a problem with water homeostasis.  Hyponatraemia = over-hydration; hypernatraemia = dehydration.  

The role of potassium is often under-appreciated. Depletion of total body potassium (e.g. after vomiting, diarrhoea or diuretic use) can result in hyponatraemia; replenishing K^+^ stores can help to correct this [@rose1986].  


## Renal water excretion

The kidneys are able to respond to purturbations in water balance by generating a dilute or a concentrated urine, varying U~Osm~ in the range 50 - 900 mOsm/kg [**REF**].  

Production of a `dilute urine` (i.e. excretion of free water) relies on three processes:  

1. glomerular filtration (of water and solute)  
2. generation of lumenal free water in the water-impermeable diluting segment (thick ascending loop of Henle and distal convoluted tubule)  
3. excretion of free water in water-impermeable collecting ducts in the absence of anti-diuretic hormone (ADH)  

<br>

Production of a `concentrated` urine (i.e. retention of free water) relies on:  

1. the generation of a concentrated inner medulla (due to the action of countercurrent multiplier in the loop of Henle and urea recycling);  
2. the reabsorption of water from the collecting ducts in the presence of ADH  

<br>
<br>

The range over which the kidneys can vary U~Osm~ may be limited by anything that can limit these processes (e.g. chronic renal insufficiency, diuretics, unregulated ADH secretion).  The ability of the kidneys to excrete free water is determined by U~Osm~ and by the total osmolar content of the urine, as we shall see \@ref(eq:UOsm1).  A large osmolar load can drive a solute diuresis; a limiting amount of filtered solute can limit water excretion.  

## Urine osmolality {#UOsm}

When an `osmolar load` (OL) is excreted in a discrete `volume` of urine (V), those two variables will determine the urine `osmolality` (U~Osm~):

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{urine osmolality, } U_{Osm} = \frac{OL}{V}
    (\#eq:UOsm1)
\end{equation}

which, when re-arranged becomes:

\begin{equation}
  \text{urine volume, } V = \frac{OL}{U_{Osm}}
    (\#eq:UOsm2)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

The reciprocal relationship between V and U~Osm~ means that the maximum urine volume used to excrete an osmolar load is determined by the lowest achievable urine osmolality in diuresis (and the minimum urine volume by the maximum possible urine osmolality in antidiuresis):

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{maximum urine volume, } V_{max} = \frac{OL}{U_{Osm_{min}}}
    (\#eq:UOsmmin)
\end{equation}

\begin{equation}
  \text{minimum urine volume, } V_{min} = \frac{OL}{U_{Osm_{max}}}
  (\#eq:UOsmmax)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

These simple relationships can be used to explore a number of phenomena, such as:  

+ explaining why drinking seawater causes dehydration  
+ explaining why giving 0.9% NaCl can exacerbate hyponatraemia in some circumstances  
+ calculating the water intake that would cause hyponatraemia  
+ explaining why poor diet (low dietary solute intake) can cause hyponatraemia    

These are considered in more detail in [Appendix 1](#app1). 

## Hyponatraemia

Hyponatraemia is caused by free water excess.  When this is associated with reduced plasma tonicity, this can cause cerebral oedema.  

### Correction for hyperglycaemia  
However, hyponatraemia can result from an influx of water into the vascular (and interstitial) space in presence of an abnormaly high concentration of a plasma osmole.  The commonest such clinical scenario is that of hyperglycaemia.  (Hyponatraemia in this context is not dangerous *per se* because plasma tonicity is maintained near normal by glucose, an effective osmole.)  
<br>
<br>

The value that P~Na~ will correct to with resolution of hyperglycaemia can be estimated: 

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{corrected } P_{Na}, cP_{Na} = P_{Na}+2.4 \times \frac{P_{glucose}-5.5\text{mM}}{\text{5.5mM}}
  (\#eq:gluccorr)
\end{equation}
NB alternatively this can calculated by adding 0.4 mM to measured P~Na~ for every 1 mM rise in P~glucose~.  Also remember to add in adjustment for HD patients! [**REF**]
</div>\EndKnitrBlock{eqnpanel}

### Urine sodium  

In the steady-state, urinary sodium excretion will reflect sodium intake.  On a normal Western diet, daily NaCl intake might be ~XXXg (=XXXmmoles) [**REF**].  If this were excreted in 2L or urine, then U~Na~ would be ~XXXXmM.  
<br>
<br>

When volume homeostasis is threatened and the renin-angiotensin-aldosterone system is activated, renal sodium reabsorption is stimulated and U~Na~ drops.  As a rule-of-thumb, U~Na~ is < 30 mM in volume depletion:  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  U_{Na}<30\text{mM }=\text{low effective artieral blood volume}
  (\#eq:UNavolumestatus)
\end{equation}</div>\EndKnitrBlock{eqnpanel}

This threshold was derived in an elegant study of patients with hyponatraemia in which *bona fide* volume depletion was determined retrospectively by a positive response to a crystalloid bolus [**REF**].  It is more accurate to say that low U~Na~ refects low effective arterial blood volume (EABV) rather than volume depletion *per se*).  This hypothetical concept encompasses both intravascular volume and vascular tone, and is useful in explaining why the RAAS is activated in hypervolaemic (but low-perfusion) states such as heart failure and cirrhosis. [**REF**]  
<br>
<br>

U~Na~ will not accurately report EABV in the presence of any drug or disease that perturbs renal sodium excretion, such as:  

+ diuretics  
+ salt-wasting nephropathies (Addison's, Barrter, Gitelman)  
+ etc  


## Estimate of total body water


\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{total body water, }TBW = \text{body weight}\times k
  (\#eq:TBW)
\end{equation}

where k= 0.6 in men; 0.5 in women, elderly men or obesity and 0.45 in elderly women.  
</div>\EndKnitrBlock{eqnpanel}

Fat is ~70% water; adipose tissue is ~10% water.  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}

  \text{water excess } = TBW \times (1-\frac{P_{Na}}{140})
  (\#eq:aqxs)
\end{equation}</div>\EndKnitrBlock{eqnpanel}


### Diagnoistic algorithm in hyponatraemia

\BeginKnitrBlock{algpanel}<div class="algpanel">**Order of operations in hyponatraemia:**  
  
1. confirm true hypotonic hyponatraemia
    + correct for [glucose] in hyperglycaemia
    + check P~Osm~
2. determine clinical volume status  
3. check U~Osm~ (< 100 mM suggests urine water excretion limited by unregulated ADH or low solute load)  
4. check U~Na~ (< 30 mM suggests low effective arterial blood volume)  


And remember to consider:  

+ is there total body K depletion?
+ is solute intake low?
</div>\EndKnitrBlock{algpanel}

## Free water clearance

### Calculating free water clearance

The quantitative contribution of the kidney to water homeostasis can be determined by calculating the osmolar- or electrolyte-free water clearance.  

A dilute urine can be thought of as comprising a volume of urine that is isotonic with plasma PLUS a volume of "free" water.  A concentrated urine can be thought of as a volume of isotonic urine MINUS a volume of "free" water.  `Free water clearance` is a hypothetical concept that determines this volume of "free" water in the urine.  

Traditionally, this was calculated by first determinine the total clearance of osmoles and subtracting this from urine flow: 


\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{osmolar clearance, }C_{Osm} = \frac{U_{Osm} \times V}{P_{Osm}}
  (\#eq:COsm)
\end{equation}

\begin{equation}
  \text{free water clearance, }C_{H_{2}O} = V-C_{Osm}=V \times(1-\frac{U_{Osm}}{P_{Osm}})=\frac{OL}{U_{Osm}}\times(1-\frac{U_{Osm}}{P_{Osm}})
  (\#eq:CFW)
\end{equation}

\begin{equation}
  \text{free water reabsorption, }T^{C}_{H_{2}O} = C_{Osm}-V 
  (\#eq:RFW)
\end{equation}
</div>\EndKnitrBlock{eqnpanel}

However, as not all urinary osmoles are [*effective* osmoles](#tonicity) with respect to cell membranes, it makes more sense to determine the clearance of water that is free from only effective osmoles when working out how renal water clearance is likely to affect P~Na~.  Therefore, it is usually preferable to calculate electrolyte-free water clearance:

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{electrolyte-free water clearance, }C_{H_{2}O}(e) = V\times(1-\frac{U_{Na}+U_{K}+U_{OEOs}}{P_{Na}+P_{OEOs}})\\ \approx\frac{OL}{U_{Osm}}\times(1-\frac{U_{Na}+U_{K}}{P_{Na}})
  (\#eq:CFWE)
\end{equation}

Other effective osmoles (OEOs) may be: glucose, mannitol...
</div>\EndKnitrBlock{eqnpanel}

Most of the time, this can be simplified by considering only the dominiant urinary cations, sodium and potassium.  The urine:plasma electrolyte ratio is a related concept:  

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{electrolyte clearance, }C_{El} = \frac{U_{Na+K}\times V}{P_{Na}}
  (\#eq:CEl)
\end{equation}

\begin{equation}
  \text{urine:plasma electrolyte ratio, U:P(e)} = \frac{U_{Na}+U_{K}}{P_{Na}}
  (\#eq:UPratio)
\end{equation}
</div>\EndKnitrBlock{eqnpanel}

### Clinical utility of free water clearance

The main clinical application of free water clearance is in determinine the quantitative contribution of the kidneys to the pathogenesis of hyponatraemia.  This can help if diagnosing the *cause* of hyponatraemia and in guiding *rational therapy*.  

Hyponatraemia will ensue when free water intake exceed free water clearance.  A low free water clearance, in the context of hyponatraemia, indicates some sort of problem with the ADH-kidney axis. 
Free water clearance can be used to determine the extent to which water intake should be restricted (in cases of euvolaemia or volume-expanded hyponatraemia where this should help to correct hyponatraemia).  A meticulous approach entails calculating $C_{H_{2}O}(e)$ and using this to set a value for the daily water intake that would result in hyponatraemia - accounting for any insensible water losses and obligate free water intake.  

A more straightforward approach - and one that can be followed when urine flow rate has not been documented - is to approximate $C_{H_{2}O}(e)$ from the urine:plasma electrolyte ratio (sometimes known as the "Furst ratio") - see Furst et al (Am J Med Sci, 2000).  The Furst formula makes various assumptions about body size, cation intake and insensible water losses in order to give a very approximate estimate of urinary free water excretion.  

The estimates for net free water loss (and the restriction on water intake that would be required to raise plasma sodium) are as follows, with the duration being that required for 1L of urine output: 

+----------------------+-------------------------------+-------------------+
|U:P electrolyte ratio | estimated net free water loss | max fluid intake  |
+======================+===============================+===================+
| \>1.0                | 800 ml                        | 0 ml              |
+----------------------+-------------------------------+-------------------+
| 0.5 -- 1.0           | 800 - 1300 ml                 | 500 ml            |
+----------------------+-------------------------------+-------------------+
| \<0.5                | 1300 - 1800 ml                | 1000 ml           |
+----------------------+-------------------------------+-------------------+

<br>
<br>

Based on this, Joel Topft and others have proposed an approximate guide to fluid restriction:  

+----------------------+---------------------------------+
|U:P electrolytes      | set fluid restriction to...     |
+======================+=================================+
| UNa + UK \> PNa      | 500 ml (and give furosemide bd) |
+----------------------+---------------------------------+
| UNa + UK \~ PNa      | 500 - 800 ml                    |
+----------------------+---------------------------------+
| UNa + UK \< PNa      | \>1000 ml                       |
+----------------------+---------------------------------+


## Hypernatraemia

In contrast to hyponatraemia, which may pose a diagnostic conundrum, in hypernatraemia it is almost always easy to work out the underlying cause.  Hypernatraemia is caused by loss of free water (dehydration).  Because the thirst resoponse is such a powerful negative feedback controlled of P~Osm~, in most cases hypernatraemia arises through *lack of access to water* rather than excessive water losses *per se*.  This is often iatrogenic: a classic example being the patient with chronic diabetes insipidus who, having been used to drinking many litres of water per day, becomes hypernatraemic when they are admitted to hospital and their access to water is limited.  

The treatment of hypernatraemia is simple: give more free water (either enterally or as intravenous 5% glucose).  The total body water deficit can be estimated as follows:

\BeginKnitrBlock{eqnpanel}<div class="eqnpanel">\begin{equation}
  \text{water defecit } = TBW \times (\frac{P_{Na}}{140}-1)\approx \frac{P_{Na}-140}{3}
  (\#eq:aqdef)
\end{equation}

and total body water is estimated thus:

\begin{equation}
  \text{total body water, }TBW = \text{body weight}\times k
  (\#eq:TBW)
\end{equation}

where k= 0.6 in men; 0.5 in women, elderly men or obesity and 0.45 in elderly women.  
</div>\EndKnitrBlock{eqnpanel}

Armed with this estimate, fluid may be prescribed at an appropriate rate to achieve gradual restoration of normal plasma tonicity.  

## Other useful indices

### FEUrate

Urate transport in PCT is coupled to sodium transport.  Volume depletion will stimulate Na reabsorption in PCT and hence also urate reabsorption.  

In normal subjects, FEurate is 4 -- 11%.  

In volume depletion (or states of low EABV), FEurate is low (< 4%).  
In volume expansion, SiADH or renal salt wasting, FEurate is high (> 11%).  
