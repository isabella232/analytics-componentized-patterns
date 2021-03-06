[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

## Analytics Componentized Patterns

From sample dataset to activation, these componentized patterns are designed to help you get the most out of [BigQuery ML](https://cloud.google.com/bigquery-ml/docs) and other Google Cloud products in production.

### Retail use cases
* Recommendation systems:
  * How to build a recommendation system on e-commerce data using BigQuery ML. ([Code][recomm_code] | [Blog Article][recomm_blog])
* Propensity to purchase model:
  * How to build an end-to-end propensity to purchase solution using BigQuery ML and Kubeflow Pipelines. ([Code][propen_code])
* Activate on Lifetime Value predictions: 
  * How to predict the monetary value of your customers and extract emails of the top customers to use in Adwords for example to create similar audiences. Automation is done by a combination of BigQuery Scripting, Stored Procedure and bash script. ([Code][ltv_code])
* Clustering:
  * How to build customer segmentation through k-means clustering using BigQuery ML. ([Code][clustering_code])

[recomm_code]: retail/recommendation-system/bqml
[recomm_blog]: https://medium.com/google-cloud/how-to-build-a-recommendation-system-on-e-commerce-data-using-bigquery-ml-df9af2b8c110
[propen_code]: retail/propensity-model/bqml
[ltv_code]: retail/ltv/bqml
[clustering_code]: retail/clustering/bqml


## Disclaimer
This is not an officially supported Google product.

All files in this repository are under the [Apache License, Version 2.0](LICENSE.txt) unless noted otherwise.