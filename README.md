# Grip Strength SOEP Survey Data

This repo contains data from the following research paper:
> Steiber N (2016) Strong or Weak Handgrip? Normative Reference Values for the German Population across the Life Course Stratified by Sex, Age, and Body Height. PLoS ONE 11(10): e0163917. doi:10.1371/journal.pone.0163917

The research paper analyzed the grip strength data from the German Socio-Economic Panel (2006–2014).
The dataset is from:
- Table 1. Normative Reference Values of Handgrip Strength for German Men.
- Table 2. Normative Reference Values of Handgrip Strength for German Women.

Both tables are combined in one file "hand_grip_strength_SOEP_normative".
The dataset is provided in both .json and .csv format.

In addition to simply the data from the tables, the "Age-group-specific SD" (SD - standard deviation) is also provided.
It is calculated simply by subtracting "Risk threshold", which is defined as 1 SD below the mean, from "Mean HGS" (HGS - hand grip strength).
I hope this makes the data about grip strength more accessible for anyone looking to study these results.

I originally extracted this for the [grip calculator tool on StrengthDiagnostics.com.](https://www.strengthdiagnostics.com/grip-calculator)
Here is also a short blog post with more info on the grip calculator: https://www.strengthdiagnostics.com/blog/grip-calculator-launch