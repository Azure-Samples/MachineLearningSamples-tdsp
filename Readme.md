# TDSP Project Dashboard

## Summary
**TDSP Project Dashboard**

This is the project dashboard where you put key project information (for example, a project summary, with relevant links). In your actual project, replace the rest of the content with project-specific summary.

## Team Data Science Process From Microsoft (TDSP)

This repository contains an instantiation of the [**Team Data Science Process (TDSP) from Microsoft**](https://github.com/Azure/Microsoft-TDSP) for project **Azure Machine Learning**. The TDSP is an agile, iterative, data science methodology designed to improve team collaboration and learning. It facilitates better coordinated and more productive data science enterprises by providing:

- a [lifecycle](https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/lifecycle-detail.md) that defines the steps in project development 
- a [standard project structure](https://github.com/Azure/Azure-TDSP-ProjectTemplate)
- artifact templates for reporting
- tools to assist with data science tasks and project execution

## Information About TDSP In Azure Machine Learning
When you instantiate the TDSP from Azure Machine Learning, you get the TDSP-recommended standardized directory structure and document templates for project execution and delivery. The workflow then consists of the following steps:

- modify the documentation templates provided here for your project
- execute your project (fill in with your project's code, documents, and artifact outputs)
- prepare the Data Science deliverables for your client or customer, including the ProjectReport.md report.

We provide [instructions on how to instantiate and use TDSP in Azure Machine Learning](https://aka.ms/how-to-use-tdsp-in-aml).

## The Data Science Lifecycle 
TDSP uses the data science lifecycle to structure projects. The lifecycle defines the steps that a project typically must execute, from start to finish. This lifecycle is valid for data science projects that build data products and intelligent applications that include predictive analytics. The goal is to incorporate machine learning or artificial intelligence (AI) models into commercial products. Exploratory data science projects or ad hoc/on-off analytics projects can also use this process, but in this case some steps of this lifecycle may not be needed.    

Here is a depiction of the [TDSP lifecycle](https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/lifecycle-detail.md). 

The TDSP data science lifecycle is composed of four major stages that are executed iteratively. This includes:

* Business Understanding
* Data Acquisition and Understanding
* Modeling
* Deployment

These stages should, ideally, be followed by customer acceptance for successful projects. 

If you are using a different lifecycle schema, such as [CRISP-DM](https://wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining), [KDD, or your own custom process that is working well in your organization, you can still use the TDSP in the context of those development lifecycles. 

For reference, see a more [detailed description of the TDSP life-cycle](https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/lifecycle-detail.md). That version also provides additional documentation templates that are associated with each phase of the TDSP lifecycle.

## Documenting Your Project
Refer to [TDSP documentation templates](https://github.com/Azure/Azure-TDSP-ProjectTemplate) to see how you can document your project for efficient collaboration and reproducibility. In the current Azure Machine Learning TDSP documentation template, we recommend that you include all the information in the [ProjectReport](https://github.com/amlsamples/tdsp/blob/master/docs/deliveralbe_docs/ProjectReport.md) file. This template should be filled out with information that is specific to your project. 

In addition to the [ProjectReport](https://github.com/amlsamples/tdsp/blob/master/docs/deliveralbe_docs/ProjectReport.md), which serves as the primary project document, we provide another template, [ProjectLearnings](https://github.com/amlsamples/tdsp/blob/master/docs/ProjectLearnings.md), to include any learnings and information, which may not be included in the primary project document, but still useful to document. 

Documents received from a customer can be stored in .\docs\dustomer\_docs. Documents prepared for sharing information with a customer (for example, ProjectReport, graphs, tables etc.) can be stored in .\docs\deliveralbe\_docs.

## Project Folder Structure
The TDSP project template contains following top-level folders:
1. **code**: Contains code
2. **docs**: Contains necessary documentation about the project
3. **sample_data**: Contains **SAMPLE (small)** data that can be used for early development or testing. Typically, not more than several (5) Mbs. Not for full or large data-sets.

**NOTE:** 
Make sure other than the readme.md file, all documentation-related content (text, markdowns, images, other document files) that are NOT used during the project execution must reside in the folder named “docs” (all lowercase). This is a special folder ignored by Azure Machine Learning execution so that contents in this folder do not get copied to compute target unnecessarily. Objects in this folder also don’t count towards the 25-MB cap for project size, so you can store large image files needed in your documentation for example. They are still tracked by Git through Run History. 

## Project Planning And Execution
To deploy [Visual Studio Online (Team Services)](https://azure.microsoft.com/en-us/services/visual-studio-team-services/) for planning, managing and executing your data science projects, detailed instructions are provided [here](https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/project-execution.md).

## Release Notes
Release of this template is associated with the preview release of Azure Machine Learning (September 2017). We are continuously improving TDSP based on customer experience and feedback, and releasing new features. Refer to [TDSP](https://github.com/Azure/Microsoft-TDSP) page for more information. 

## Ask Questions
We would love to hear back from your own experience with the TDSP. Should you have any questions or suggestions, create a new discussion thread on the [Issues Tab](https://github.com/Azure/Microsoft-TDSP/issues).

