---
layout: post
title: CS update
date: '2022-07-08'
categories: CS oyster methods
tags: CS BSA results
---
[link to previous posts](https://github.com/ocattau/notebook-2/blob/master/_posts/2021-12-06-CS7_BSAinspection.md)

# Citrate-Synthase for NOPP gigas ploidy temp 2021 experiment
## Code for caluclating Bovine Serum Assay Protein Results and Citrate-synthase Assay Results
1. batch 1 samples 1-23 [here](https://github.com/mattgeorgephd/NOPP-gigas-ploidy-temp/blob/main/202107_EXP2/citrate_synthase/CS%20script%20samples%201-23.Rmd)
2. batch 2 samples 24-48 [here](https://github.com/mattgeorgephd/NOPP-gigas-ploidy-temp/blob/main/202107_EXP2/citrate_synthase/CS%20script%20samples%2024-48.Rmd)
3. batch 3 samples 49-70 [here](https://github.com/mattgeorgephd/NOPP-gigas-ploidy-temp/blob/main/202107_EXP2/citrate_synthase/CS%20script%20samples%2048-72.Rmd)
4. compiled results 1-70 [here](https://github.com/mattgeorgephd/NOPP-gigas-ploidy-temp/blob/main/202107_EXP2/citrate_synthase/CS_script_results_all.Rmd)

## Standard Plots
1. Citrate-Synthase Standards 
- ![](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/standards%20for%20CS%20samples%201-70.png)
2. Bovine Serum Assay Standards
- ![](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/BSA%20standards%20samples%201-70.png)
3. Positive Controls, Backgrounds Controls
- ![](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/positive%20control.png)

## Finding Outliers for any redos 
1. See full results list [here](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/results/result_1-70.csv)
2. plot time on X axis and Absorbance on Y axis, redo if there is a flatline example below 
- Batch 1:every sample needs to be redone
- ![batch1](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/batch%201.png)
- Batch 2: redo samples X47, X48, N41, R62, M46, N47 based on flatlines
- ![batch2](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/batch%202.png)
- Batch 3: looks great! 
- ![batch3](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/batch%203.png)
___
3. plot Protein content vs Absorbance (a measure of CS) to see if there are any negative values or outliers 
- I would redo R60, R51, R59 due to negative values, and also N49 and N57 for being outliers
- ![batch_plot](https://raw.githubusercontent.com/mattgeorgephd/NOPP-gigas-ploidy-temp/main/202107_EXP2/citrate_synthase/plots/batch%20plot%20with%20labels.png)
