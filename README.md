# Aerial Image Classification

## Link to the Microsoft DOCS site

The detailed documentation for this real world scenario includes the step-by-step walkthrough:

[https://review.docs.microsoft.com/en-us/azure/machine-learning/preview/scenario-aerial-image-classification](https://review.docs.microsoft.com/en-us/azure/machine-learning/preview/scenario-aerial-image-classification)

## Link to the Gallery GitHub repository

The public GitHub repository for this real world scenario contains all the code samples:
[https://github.com/Azure/MachineLearningSamples-AerialImageClassification](https://github.com/Azure/MachineLearningSamples-AerialImageClassification)

## Overview

In this scenario, we train machine learning models to classify the type of land shown in aerial images of 224-meter x 224-meter plots. Land use classification models can be used to track urbanization, deforestation, loss of wetlands, and other major environmental trends using periodically collected aerial imagery. After training and validating the classification model, we will apply it to aerial images spanning Middlesex County, MA -- home of Microsoft's New England Research & Development (NERD) Center -- to demonstrate how these models can be used to study trends in urban development. This example demonstrates how to use Azure Machine Learning (AML) Workbench to coordinate distributed training and operationalization using the [Microsoft Machine Learning for Apache Spark (MMLSpark)](https://github.com/Azure/mmlspark) package on an [Azure HDInsight Spark](https://azure.microsoft.com/en-us/services/hdinsight/apache-spark/) cluster.

## Key components needed to run this scenario
- An [Azure account](https://azure.microsoft.com/en-us/free/) (free trials are available), which will be used to create an HDInsight Spark cluster with 40 worker nodes.
- [Azure Machine Learning Workbench](https://review.docs.microsoft.com/en-us/azure/machine-learning/preview/overview-what-is-azure-ml)
- [AzCopy](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy), a free utility for coordinating file transfer between Azure storage accounts.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (for example, label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
