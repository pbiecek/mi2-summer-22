# survxai 1.0 - implementation of the new version of the R package for explaining the survival analysis models

**Mentor:** [Mateusz Krzyziński](https://www.mi2.ai/the-team.html#mateusz-krzyziński)

**Support mentor:** [Hubert Baniecki](https://hbaniecki.com)

## What is the project about?
This project aims to create an R package with explainable artificial intelligence methods directly targeting survival analysis models. 
It will be a new, refreshed version of the existing [**survxai** package](https://mi2datalab.github.io/survxai/) extended with new functionalities. 
In addition, **survStudio** - the tool that automates the explanatory analysis of survival models - 
will be built on its basis (based on [modelStudio](https://modelstudio.drwhy.ai)).

### TS;WM 
#### Survival analysis
**Survival analysis** is used to predict the time until some specific event occurs for a selected individual in the considered population. 
This time is estimated based on various features (covariates) describing this individual. 
However, due to the presence of **censored data**, regression is not an appropriate approach.
The most common type of censoring is right-censoring — which means that part of the population did not experience the event during the study (data collection). 
Survival analysis models have been developed to deal with such data.

#### eXplainable AI in survival analysis
The flexibility of machine learning models is expected to lead to more accurate predictions than classical statistical models. 
However, ML models often work as black-box models. Hence, it is essential to be able to explain their decisions. 
The natural prediction of survival analysis models is some function (the survival function or cumulative hazard function). 
It motivates the development of explanation methods explicitly designed to evaluate survival analysis models. 
Unfortunately, the common problem is that the methods described in the literature are often not available for easy use 
due to the lack of open-source packages.

For more information, please refer to the [article](https://medium.com/responsibleml/responsible-machine-learning-for-survival-analysis-e0a24939d49f).

## Why is the project important?
- In the case of survival analysis, which is often used in the medicine or insurance industry, responsible modeling is crucial. 
- The package for explaining the survival analysis models is handy. 
The old version of the package, although not regularly updated, is still used by users, as evidenced by 15K downloads and recently created issues.
- There is still no alternative package offering a range of explanations for survival analysis models.
- After improving the style of the charts in line with Dr. Why Styleguide (DALEX style), the package's visual explanations can be used more often in research papers. 
One of the most popular packages related to survival analysis is [survminer](https://rpkgs.datanovia.com/survminer/), 
which allows to make nice visuzalizations easily and evaluate a simple Cox model.


## What shall be completed by the end of the project?
- Updating the survxai package to the DALEX-compatible version (in terms of the logic/structure, the way of usage, and the style of the created visual explanations); 
the way it is used and the style of the created visual explanations);
- Adding new types of explanations to the package - e.g., survSHAP (currently the method under development),
[survLIME](https://www.sciencedirect.com/science/article/abs/pii/S0950705120304044?dgcid=rss_sd_all);
- Updating the package documentation and creating new vignettes;
- Experiments related to the application of functional data analysis to explain survival models and the use-cases of the package;
- Enabling the creation of automated, interactive explanations of the model - survStudio based on modelStudio (progress depends on the fulfillment of other points).

## What intern(s) will learn during the summer project?
- Mathematical foundations of survival analysis and methods of their explanation.
- Training survival analysis models, handling censored data.
- Creating an R package.
- Creating visualization of explanations.

## Follow-up possibilities
- Collaborating on writing a paper describing the package.
- Further development of survStudio tool.
