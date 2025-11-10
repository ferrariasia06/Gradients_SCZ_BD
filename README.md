1. UCLA_BD-SCZ --> Original script from Bin with categorical analyses and gradients computation.
2. PLS_gradients --> PLS with only one latent variable run on one gradient at a time. Two models: the first with diagnosis included as a behavioral variable, and the second without.
3. PLS_gradients_noreg_age_gender --> Same as number one, but instead of regressing out age and gender, they are included in the model as behavioral variables.
4. PLS-gradients_Chapman_QA --> PLS with only one latent variable run on one gradient at a time, including the whole sample. Two models: the first with regression of age and gender, and the second without the regression and including them as behavioral variables.
5. PLS_FC --> PLS with only one latent variable run on FC. Four models: the first with diagnosis included as a behavioral variable and all the nodes, the second with diagnosis using only the upper 10% of FC, the third without diagnosis and all FC, and the fourth without diagnosis and the upper 10% of FC.
6. PLS-gradients_Chapman_QA_3LV --> PLS with only three latent variables run on one gradient at a time, including the whole sample with regression of age and gender.
7. PLS_gradients_mult_comp --> PLS with diagnosis included as a behavioral variable, regression of age and sex, two models: the first with 3 latent variables and the second with 10 latent variables.

