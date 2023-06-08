# Day 4

## Seminar: Exploring "fishy" data - an adventure in multivariate statistics and the cult of J.W. Tukey
*Speaker: Sam Legget*

There is a lot of uncertainty in statistics with archaeology. 
Many statisticians are moving beyond using P-values.
In computational archaeology, P-values are generally unhelpful.

A new approach is exploratory data analysis (EDA). 
EDA is about being "actively incivise rather than passively descriptive".

Averages (and other summaty statistics) are not enough to understand your data. 
Different data can have similar summary statistics.

Sam's current research involves using meta-analysis to investigate how fish have been part of human diets. 
Sam uses data from human remains to understand historic diets.
Most people plot this data on two axes -- carbon on one axis and nitrogen on the other.
More recent analyses also include sulphur content to add a third dimension.
Analysis of where someone came from using water is difficult, as humans have throughout history bottled and imported drinks such as beer and wine.

Sam was able to use EDA to analyse her complex data.
Looking at postcranial bones to investigate later life diets, Sams data were hierachical and nested.
Using multivariate statistics, she was able to identify 3 distinct clusters in the data, which corresponded to 3 distinct diets.
Sam was able to use her data to suggest that there were possible adulthood fish eaters in England during the medieval period.

## Statistics
There are two main types of statistics: descriptive and inferential.
Descriptive statistics are used to summarise data.
Inferential statistics are used to make inferences (and predictions) about the world based on the observed data.

### Descriptive statistics
Descriptive statistics include:

- Distribution and central tendency
- Mean, median, standard deviation

Plots can include normal distributins and box plots. 
These plots can show outliers, but you should be careful with them.
Make sure to report any decisions on outliers transparently.

### Inferential statistics
There are lots of ways to do inferential statistics.
Which method to use can be decided by considering:

- The nature of the research question
- The nature of the data
- the objectives

#### Linear regression
Linear regressions models show linear relationships between prediction variables and outcome variables.
It is important to check the assumptions each time you use a model.

#### Null hypothesis testing
Hypotheses are claims researchers make about the world based on some data.
There are two possible errors in decision making:

- Type 1 error - incorrectly reject H0
- Type 2 error - incorrectly retain H0

## Practical
We are using the following packages to run different statistical analyses: tidyverse, lme4, ggfortify.

The research questions we want to ask are:

- Is the increase of house price associated with Energy bill?
- Is the increase of house price associated with Alcohol Consumption?
- Is the increase of house price associated with Location (Rural vs Urban)?
- Is Deprivation (measured as SIMD) associated with increase of house price?
- How statistically significant is the rent increase across Scotland?
- What factors are most associated with deprivation and rent increases?
