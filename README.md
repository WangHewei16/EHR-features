# Predicting Stroke from Electronic Health Records

With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript: 

> Soumyabrata Dev, Hewei Wang, Chidozie Shamrock Nwosu, Nishtha Jain, Bharadwaj Veeravalli, and Deepu John, A predictive analytics approach for stroke prediction using machine learning and neural networks, Healthcare Analytics, 2022.

If you find our work useful in your research, please consider citing our [paper](https://www.sciencedirect.com/science/article/pii/S2772442522000090).

```
@article{DEV2022100032,
title = {A predictive analytics approach for stroke prediction using machine learning and neural networks},
journal = {Healthcare Analytics},
volume = {2},
pages = {100032},
year = {2022},
issn = {2772-4425},
doi = {https://doi.org/10.1016/j.health.2022.100032},
author = {Soumyabrata Dev and Hewei Wang and Chidozie Shamrock Nwosu and Nishtha Jain and Bharadwaj Veeravalli and Deepu John},
}
```

This code is only for academic and research purposes.

## Code Organization
All codes are written in `R` and `python`. 

### Code 
The script to reproduce all the figures, tables in the paper are as follows:
+ `main.R`: main scripts in R
+ `boxplots_adding.py`: script to plot the boxplot of adding features
+ `boxplots_removing.py`: script to plot the boxplot of removing features
+ `PCA8-evaluation.R`: pca analysis stuffs
+ `top3-features.R`: Results obtained by considering top-3 features
+ `More details.ipynb`: Other experiments
+ `CHADS2_stroke_proportion.ipynb`: Results about the proportion of cases with a stroke event as predicted by CHADS<sub>2</sub> for each score level respectively
+ `CNN_all_Features.ipynb`: Results obtained by CNN model considering all features
+ `MPL_all_Features.ipynb`: Results obtained by MPL model considering all features
+ `SVM_all_Features.ipynb`: Results obtained by SVM model considering all features
+ `LASSO_all_Features.ipynb`: Results obtained by LASSO model considering all features
+ `ElasticNet_all_Features.ipynb`: Results obtained by LASSO model considering all features

### Results 
We also share the results obtained in our random downsampling experiments. The results obtained with the various benchmarking approaches is found in `my_results.csv`.
