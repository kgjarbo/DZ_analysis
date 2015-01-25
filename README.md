# DZ_analysis
Scripts and functions for analyzing Danger Zone data and generating output of results

----
2015-01-25
----
Initially, all code will be written in MATLAB to work with the existing data files. Future versions of the code will written in Python as the CoAx Lab transitions from MATLAB.

Scripts and functions to be included:
  - DZ_batch_analyze.m
    - Script to run all sub-functions for group analysis of DZ data
    - Options to analyze data for specific versions of DZ
  - DZ_bias.m
    - Compute bias scores for individual datasets
    - Plots bias scores across all trials
    - Generalized for all versions of Danger Zone
  - DZ_grubbs_test.m
    - Performs Grubb's test on individual datasets to remove outlier trials
    - Saves a list of removed trials
  - DZ_catch_filter.m
    - Computes catch trial accuracy for individual datasets
    - Datasets with catch trial accuracy < 50% will be excluded from group analyses
    - Saves a list of excluded datasets

Functions for between- and within-subjects ANOVAs will also be included.
