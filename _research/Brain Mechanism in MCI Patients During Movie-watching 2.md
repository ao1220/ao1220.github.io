---
title: "Brain Mechanism in MCI Patients During Movie-watching 2"
collection: research
type: "Undergraduate course"
permalink: /research/Brain Mechanism in MCI Patients During Movie-watching 2
venue: "University of Electronic Science and Technology of China, Key laboratory for Neuroinformation of Ministry of Education"
date: 2023-11-01
location: "ChengDu, China"
---

EEG Power and Source Analysis in People with MCI during Movie-watching
------

Introduction
======
In the same paradigm, we also focus on the changes in EEG power and neural current density induced by MCI.

Results
======
The results .
<br>
![Figure 2. Connection strength matrix](/images/single.jpg)
Figure 2. Connection strength matrix
<br>
![Figure 3. ANOVA and post-hoc t-test](/images/fig1.jpg)
Figure 3. ANOVA and post-hoc t-test. (A) Results of ANOVA interactions across frequency bands, the color bar indicates F-values (p<0.05), and (B) post-hoc t-test results, the color bar indicates t-values (p<0.05, FDR corrected).
<br>
![Figure 4. line graph](/images/fig2-v3.jpg)
Figure 4. (A) Negative edges and the corresponding straight-line graphs. (B) Positive edges and the corresponding line graphs. Negative edges: t-values < 0; positive edges: t-values > 0. T-test: ΔPSI MCI vs ΔPSI NC; Δ = PSI high-recall – PSI low-recall, p<0.05; error bar: SE. <br>
<br>
Furthermore, the changes in synchronous connectivity are related to cognitive function which has been suggested by the correlation with neuropsychological assessment scores.
<br>
![Figure 5. Connection strength matrix](/images/fig3-v2.jpg)
Figure 5. Scatterplots between PSI differences of negative edge high minus low states and neuropsychological assessment scores for each frequency band. The orange and blue circles indicate the NC and MCI subjects, respectively. The black line and shaded area show the estimated regression curves and 95% confidence intervals derived from regression analysis. r: Pearson correlation coefficient; p: p-value.
<br>
![Figure 6. Connection strength matrix](/images/fig4-v2.jpg)
Figure 6. Scatterplots between PSI differences of positive edge high minus low states and neuropsychological assessment scores for each frequency band. The orange and blue circles indicate the NC and MCI subjects, respectively. The black line and shaded area show the estimated regression curves and 95% confidence intervals derived from regression analysis. r: Pearson correlation coefficient; p: p-value.

Methods
======
For each participant, the global normalized EEG power density at the scalp electrode level was evaluated. The relative power in specific band was defined as power of specific band/total power across full band. <br>
For source analysis, a three-concentric sphere head model according to previous papers was used to generate the leadfield matrix. Then, a geometrically triangular grid based on the standard brain (normalized by the radius of the scalp) were used in the equivalent source model (the mesh was down-sampled to 6144 vertexes to reduce the computational load). <br>
The eLORETA was used to estimate the cortical source activity generating scalp EEG rhythms. The input for this estimation was the EEG spectral power density computed above, and the solutions were computed EEG frequency bin-by-frequency bin .Next, the eLORETA estimates of neural current density were normalized by the following procedure. Source estimates were averaged across all frequency bins from 1 to 40 Hz and 6,144 voxels of the brain model volume, to obtain the eLORETA “mean” neural current density. Afterwards, ratios between any original eLORETA estimate of the neural current density at a given frequency bin/voxel and the eLORETA “mean” neural current density were calculated. And, normalized eLORETA source estimates of each voxel were obtained finally. <br>
It is still analyzed using the same statistical methods as the connectivity.
