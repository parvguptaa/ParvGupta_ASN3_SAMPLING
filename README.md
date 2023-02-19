# PARV GUPTA
# A comparative analysis of sampling techniques for five machine learning models

## Introduction

The goal of this project is to examine the efficacy of various sampling techniques for producing a balanced dataset for a machine learning model. The original dataset is imbalanced, so both random over-sampling and under-sampling techniques are utilized to achieve balance. Next, five distinct sampling approaches are applied to this balanced dataset, and the resulting samples are compared in terms of their accuracy using five different machine learning models.

## Sampling Techniques

The following five sampling techniques were used in this project:

1. **Simple Random Sampling:** A simple random sampling technique that assigns an equal probability of selection to each data point in the dataset.

2. **Stratified Sampling:** Stratified sampling is a sampling technique that involves dividing a population into subgroups or strata based on a specific characteristic, and then selecting samples from each stratum in proportion to the population

3. **Systematic Sampling:** The systematic sampling technique involves selecting every nth element from the population to form the sample, where n is a fixed interval determined by the researcher

4. **Cluster Sampling:** Cluster sampling is a sampling technique where the population is divided into clusters, and a sample of these clusters is randomly selected. Then, all members of the selected clusters are included in the sample
5. **Convenience Sampling:** Convenience sampling is a non-probability sampling technique where the sample is selected based on its ease of access or convenience to the researcher, rather than a random or representative selection process

## Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.

| Sampling Technique | Decision Tree | SVM | Logistic Regression | KNN | Naive Bayes |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 0.9778 | 0.8954 | 0.8917 | 0.8915 | 0.7275 |
| Systematic Sampling | 0.9813 | 0.8989 | 0.9213 | 0.9493 | 0.6854 |
| Stratified Sampling | 0.9851 | 0.8937 | 0.9217 | 0.9498 | 0.6890 |
| Cluster Sampling | **0.9868** | 0.9000 | 0.9088 | 0.9691 | 0.9235 |
| Convenience Sampling | 0.9849 | 0.9190 | 0.9322 | 0.9623 | 0.7740 |

Based on these results, it can be concluded that Cluster Sampling performs the best on all five models. Simple random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Decision Tree.

## Conclusion

In conclusion, based on the performance evaluation of different sampling techniques for this dataset, cluster sampling is highly recommended as it outperforms other sampling techniques across all models. However, it is important to note that the choice of sampling technique may vary depending on the characteristics of the dataset and the models being used. Therefore, it is recommended to consider other sampling techniques for different datasets and models.
 
