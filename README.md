## Introduction

This repository is created for Machine Learning Assignment as part of the 2018/19 Machine Learning module CS7CS4 at Trinity College Dublin.

### Getting Started

You can learn how to analyze the impact of noise on dataset for machine learning application.

### DataSet
Phase 1:

The dataset consists of data collected from heavy Scania trucks in everyday usage. The system in focus is the Air Pressure system (APS) which generates pressurised air that are utilized in various functions in a truck, such as braking and gear changes. The datasets' 
positive class consists of component failures for a specific component of the APS system. The negative class consists of trucks with failures for components not related to the APS. The data consists of a subset of all available data, selected by experts.


Phase 2:
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: [Web Link] or the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are munch more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods. 

Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

### Reseach Paper 

```markdown
The project is developed based on the study of following research papers:
1. Costa C.F., Nascimento M.A. (2016) IDA 2016 Industrial Challenge: Using Machine Learning for Predicting Failures, Advances in Intelligent Data Analysis XV. IDA 2016. Lecture Notes in Computer Science, vol 9897. Springer, Cham 
2. Gondek C., Hafner D., Sampson O.R. (2016) Prediction of Failures in the Air Pressure System of Scania Trucks Using a Random Forest and Feature Engineering. In: BostrÃ¶m H., Knobbe A., Soares C., Papapetrou P. (eds) Advances in Intelligent Data Analysis XV. IDA 2016. Lecture Notes in Computer Science, vol 9897. Springer, Cham 
3. Cerqueira V., Pinto F., SÃ¡ C., Soares C. (2016) Combining Boosted Trees with Metafeature Engineering for Predictive Maintenance. In: BostrÃ¶m H., Knobbe A., Soares C., Papapetrou P. (eds) Advances in Intelligent Data Analysis XV. IDA 2016. Lecture Notes in Computer Science, vol 9897. Springer, Cham 
4. Ozan E.C., Riabchenko E., Kiranyaz S., Gabbouj M. (2016) An Optimized k-NN Approach for Classification on Imbalanced Datasets with Missing Data. In: BostrÃ¶m H., Knobbe A., Soares C., Papapetrou P. (eds) Advances in Intelligent Data Analysis XV. IDA 2016. Lecture Notes in Computer Science, vol 9897. Springer, Cham
5. Hybrid Artificial Intelligent Systems, Spain 2013, Springer
6. Dempster, A.P., Laird, N.M., Rubin, D.B.: Maximum likelihood from incomplete data via the EM algorithm. J. R. Stat. Soc. Ser. B 39(1), 1–38 (1977) 
7. Graham, J.W.: Missing data analysis: making it work in the real world. Annu. Rev. Psychol. 60, 549–576 (2009)
8.  Mazumder, R., Hastie, T., Tibshirani, R.: Spectral regularization algorithms for learning large incomplete matrices. J. Mach. Learn. Res. 11, 2287–2322 (2010) 
9. Rubin, D.B.: Multiple Imputation for Nonresponse in Surveys. Wiley, New York (1987)

```

### Contribution 

```markdown
This project is a group assignment which is developed by following students:
1. Ankit Samantaray
2. Raksha Kodandaramu
3. Ravi Yadav

Detailed Contribution
Ravi (17318412)

    Background research on attribute noise.
    Read research paper on the impact of noise.
    Contributed to data pre-processing stage.
    Developed code for feature engineering.
    Contributed to writing the 'Result' section of the report.

Raksha (18300546)

    Read research paper on attribute noise.
    Developed code for Random Forest
    Implemented the noise introduced by adding irrelevant features.
    Written 'Limitation and Future Scope'  and 'Noise Introduction' sections of the report. 

Ankit 

    Developed function for Naive Bayes implementation.
    Read research paper on the introduction of noise on the raw dataset.
    Generated graphs for the report.
    Written 'Introduction', 'Related Work' and Dataset sections of the report.
```
After November 2018, the repository is open for the contribution.
### 
In phase 2 we have done done the analysis of Noise on Performance of Machine LearningAlgorithms

### DataSet for this phase 

We have used a famous multiclass Wine Quality Data-Set from UCI Machine Learning library which consisted of the red and white variants of the Portuguese "Vinho Verde" wine\cite{uci}. In this project, we have used only white wine dataset with 4898 instances. The data contains no missing values and consists of only numeric data. The data-set has 12 attributes and 'Quality' being the target variable which indicates the wine quality on scale of 0-10.


### Support or Contact

Having trouble with Pages?[contact us](yadavra@tcd.ie) and we’ll help you sort it out.
