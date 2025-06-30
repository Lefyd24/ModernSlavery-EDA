# Modern Slavery Analysis



* Lavelle-Hill, R., Smith, G., Mazumder, A. et al. Machine learning methods for "wicked" problems: exploring the complex drivers of modern slavery. Humanities and Social Sciences Communications 8, 274 (2021). <mcreference link="https://www.nature.com/articles/s41599-021-00938-z" index="1">1</mcreference>  https://doi.org/10.1057/s41599-021-00938-z

This project explores the drivers of modern slavery using machine learning techniques.

**Abstract:** Forty million people are estimated to be in some form of modern slavery across the globe. Understanding the factors that make any particular individual or geographical region vulnerable to such abuse is essential for the development of effective interventions and policy. Efforts to isolate and assess the importance of individual drivers statistically are impeded by two key challenges: data scarcity and high dimensionality, typical of many “wicked problems”. The hidden nature of modern slavery restricts available data points; and the large number of candidate variables that are potentially predictive of slavery inflate the feature space exponentially. The result is a “small n, large p” setting, where overfitting and significant inter-correlation of explanatory variables can render more traditional statistical approaches problematic. Recent advances in non-parametric computational methods, however, offer scope to overcome such challenges and better capture the complex nature of modern slavery. <mcreference link="https://www.nature.com/articles/s41599-021-00938-z" index="1">1</mcreference>

The analysis in the notebook addresses the challenges associated with the "small n, large p" problem, which refers to data scarcity (small n) and high dimensionality (large p) when analyzing the complex drivers of modern slavery.

## Data Sources

The data used in this analysis is from the `OOS_Data.csv` and `training.csv` files.

## Libraries Required

The following Python libraries are required to run this analysis:

*   pandas
*   scikit-learn (sklearn)

To install these libraries, use pip:

```bash
pip install pandas scikit-learn
```

## Analysis Steps

The `slavery_analysis.ipynb` notebook contains the following steps:

1.  Data loading and preprocessing
2.  Feature engineering
3.  Model training and evaluation
4.  Results interpretation

## Notebook Description

The notebook `slavery_analysis.ipynb` performs an exploratory data analysis and builds predictive models to understand the factors contributing to modern slavery. It utilizes various socioeconomic indicators and machine learning algorithms to identify key drivers and assess their impact.