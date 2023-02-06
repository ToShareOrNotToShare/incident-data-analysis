# Analyzing incidents in the offshore wind industry

## Why
Companies strive to mitigate future risks and reduce the number of incidents by learning from the past.

## How
Thanks to the [Cross-industry standard process for data mining (CRISP-DM)](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining):
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/crisp_dm.png)

## What
Comparison of various ML algorithms for the classification of incident data (structured numerical and unstructured text data).

## Short explanation
The available data sets were first explored from a business perspective and subsequently divided into a multi-class classification problem with four targets:
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/methodology_area_cm.png)

Four different Machine Learning (ML) estimators were trained on the data and three different train/test split variations were compared:
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/methodology_train_test_80.png)


![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/methodology_train_test_70_90.png)


An overview of the results for all different model and dataset variations is shown here:
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/results_summary_graph.png)

As a key takeaway, an accuracy boost of up to **10 %** was gained through feeding the additional text data into the ML models.
Different train/test-splits did only slightly change the ML model accuracy.

Some files (e.g. accessing, joining and exploring the dataset / Latent Dirichlet Allocation (LDA)/ Word metrics) are not part of this repository.
If interested, feel free to ask about more info from these parts.
