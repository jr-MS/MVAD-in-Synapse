# Introduction

This repo contains a sample notebook and a sample data of Multivaraite Anomaly Detector in SynapseML. You could try out this feature in Azure Synapse Analytics or Azure Databricks, which support Spark environment. You can know more detail and guidance in this blog: (Announcing Multivariate Anomaly Detector in SynapseML)[https://techcommunity.microsoft.com/t5/ai-cognitive-services-blog/announcing-multivariate-anomaly-detector-in-synapseml/ba-p/3122486]

# Getting started is simple
1. (Create an Anomaly Detector)[https://ms.portal.azure.com/#create/Microsoft.CognitiveServicesAnomalyDetector] to get access to the capability of Multivariate Anomaly Detector.
2. (Create a resource for Azure Synapse Analytics)[https://ms.portal.azure.com/#create/Microsoft.Synapse] to use the Synapse Studio.
3. (Create a Storage account resource)[https://ms.portal.azure.com/#create/Microsoft.StorageAccount] to upload your data for model training and anomaly detection.
4. (Create a Key Vault)[https://ms.portal.azure.com/#create/Microsoft.KeyVault] to hold Anomaly Detector key and Storage Connection String.
  * Go to Key Vault > Access policies, and grant the (Azure Synapse workspace MSI permissions)[https://docs.microsoft.com/en-us/azure/data-factory/data-factory-service-identity?context=/azure/synapse-analytics/context/context&tabs=synapse-analytics] to read secrets from Azure Key Vault.
  * Create a secret in Key Vault to hold Anomaly Detector key
  * Create a secret in Key Vault to hold Connection String of Storage account
5. Log in (Azure Synapse Analytics)[https://ms.web.azuresynapse.net/] and create a new Notebook for coding. Select ‘Manage pools’ to create a new if you don’t have one.
6. Start coding and uploading data with the sample code and sample data in this repo.


# Resources
Need support? (Join the Anomaly Detector Community)[https://forms.office.com/pages/responsepage.aspx?id=v4j5cvGGr0GRqy180BHbR2Ci-wb6-iNDoBoNxrnEk9VURjNXUU1VREpOT0U1UEdURkc0OVRLSkZBNC4u].
Contact me for more questions: jingruhan@microsoft.com
