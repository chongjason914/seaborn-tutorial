# Seaborn Tutorial - Who Pays More for Health Insurance?

## Introduction
[Seaborn](https://seaborn.pydata.org/examples/index.html) is a data visualisation library that is built on top of the Python programming language. This repository contains a 
tutorial notebook which demonstrates some of the most common visualisation techniques in the seaborn library as well as a medical cost dataset from Kaggle. I have applied 
various data visualisations to explore the distribution and relationship between the variables in the dataset.

## Data description
The [Kaggle medical cost dataset](https://www.kaggle.com/mirichoi0218/insurance) contains information about 1,338 insurance beneficiaries living in the United States and 
the corresponding amount they pay for their health insurance premium.

I have chosen this dataset for the following reasons:
- Good mix of categorical and numerical variables
- Not too many features (columns)
- Intuitive and straightforward relationship between the predictor and target variables 

Below are the description of the columns in the dataset:
- age: Age of primary beneficiary
- sex: Insurance contractor gender
- bmi: Body mass index
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: The beneficiary's residential area in the US
- charges: Individual medical costs billed by health insurance

## Notebook content
**0. Introduction**

**1. Import libraries**

**2. Import and read data**

**3. Data description**

**4. Check missing values, data types and summary statistics**

**5. Feature engineering**
- age_category
- weight_condition
- dependent

**6. Visualise distribution**
- 6.1 Categorical variables
  - 6.1.1 sns.countplot
  - 6.1.2 sns.catplot (formerly sns.factorplot)
- 6.2 Numerical variables
  - 6.2.1 sns.boxplot
  - 6.2.2 sns.distplot
  - 6.2.3 sns.kdeplot

**7. Visualise relationship**
- 7.1 sns.heatmap
- 7.2 sns.barplot
- 7.3 sns.jointplot
- 7.4 sns.scatterplot
- 7.5 sns.regplot
- 7.6 sns.lmplot
- 7.7 sns.swarmplot
- 7.8 sns.violinplot
- 7.9 sns.pointplot
- 7.10 sns.pairplot

**8. Conclusion**

## Medium article 
Link to full write-up on Towards Data Science [here](https://towardsdatascience.com/visualising-data-with-seaborn-who-pays-more-for-health-insurance-200d01892ba5).

## Follow me 
- [Facebook](https://www.facebook.com/chongjason914)
- [Instagram](https://www.instagram.com/chongjason914)
- [Twitter](https://www.twitter.com/chongjason914)
- [LinkedIn](https://www.linkedin.com/in/chongjason914)
- [YouTube](https://www.youtube.com/jasonchong914)
- [Medium](https://www.medium.com/@chongjason)
