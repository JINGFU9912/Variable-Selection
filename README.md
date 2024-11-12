# Explore the impact of environmental conditions on marathon performance in gender

**Background:** Smoking cessation remains a significant challenge, particularly for individuals with a history of major depressive disorder (MDD), who often experience higher nicotine dependence and more severe withdrawal symptoms. This study investigates the moderating effects of baseline factors, including behavioral activation (BA) and pharmacotherapy (varenicline), on smoking abstinence outcomes in this high-risk population.

**Methods:** A randomized, placebo-controlled, 2x2 factorial design was used, involving 300 adult smokers with current or past MDD. Modified Poisson regression models were applied to multiply imputed datasets to assess the impact of demographic, psychological, and physiological baseline factors. AUC and Briei were used to evaluate models.

**Results:** The results indicate that Non-Hispanic White status, lower FTCD scores, and higher Nicotine Metabolism Ratio were significant predictors of smoking abstinence, with varenicline showing a strong positive effect on cessation rates. Behavioral therapy alone did not exhibit significant variation across subgroups, while pharmacotherapy consistently improved outcomes. Overall, the models demonstrated moderate to good discrimination and calibration.

**Conclusion:** This study highlights the critical role of nicotine dependence and pharmacotherapy in smoking cessation among individuals with MDD. While behavioral activation may not uniformly enhance cessation outcomes, its interaction with smoking behaviors warrants further investigation. These findings underscore the need for personalized smoking cessation strategies tailored to individual baseline characteristics.


## Files
### report
`model_selection_report.Rmd`: The Rmarkdown version of the Model Selection report, which includes both written text interpretations and raw code used in the analysis. 

`model_selection_report.pdf`: The PDF version of the Model Selection report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis. 


## Dependencies

The following packages were used in this analysis: 

 - Data Manipulation: `tidyverse` , `dplyr`, `tidyr`, `reshape2`, `glmnet`, `mice`, `sandwich`, `lmtest`
 - Table Formatting: `knitr`, `kableExtra`
 - Data Visualization: `ggplot2`, `naniar`, `pROC`
