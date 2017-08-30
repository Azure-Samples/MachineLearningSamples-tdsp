# Instructions on how to instantiate and use TDSP in Vienna

This document provides the instructions on how to instantiate and use TDSP in Vienna. 

### Instantiating TDSP strucute and templates from Vienna template gallery
Once you open the Vienna application, the following are the step-by-step instructions that you need to take to create a new project in TDSP structure having TDSP documentation templates:

1. Start creation of a new project using the '+' sign at top left.

![Start creation of new project](./Images/Instantiation_Step1.JPG) 


2. Fill in project information (Names, Git repo location, local folder location etc.)
While creating the new project, please specify all the parameters and information in the relevant boxes, e.g. project name, directory, Git repo location, Workspace where you want the projet to be created etc. Then in teh Search box, type in TDSP. The "TDSP Template" will show up. Select that template. Then hit "Create" to create your new project in TDSP structure.

![Fill in project information](./Images/Instantiation_Step2.JPG) 

3. Examing the TDSP project structure
After your new project is created (usually in a few seconds), examine its structure. This structure is derived from the TDSP structure published [here](https://github.com/Azure/Azure-TDSP-ProjectTemplate), but with some simplifications. For example, several of the document templates are merged into one markdown, namely, [ProjectReport.md](../ProjectReport.md).

![Fill in project information](./Images/Instantiation_Step3.JPG) 


### Using the TDSP structure and templates

The template is not populated with any code, you will obverve, in the Code folder (and sub-folders). You are expected to populate the Code folder and its sub-folders with code files that are necessary for executing your project. The [ProjectReport.md](../ProjectReport.md) is a template that should be directly modified with information relevant to your project. The ProjectReport.md comes with a set of questions which help you to fill out the information on all four stages of the [Data Science Life Cycle](https://github.com/Azure/Microsoft-TDSP/blob/master/Docs/lifecycle-detail.md).

### Example end-to-end worked-out projects done using TDSP in Vienna

To facilitate your understanding on how the TDSP structure and templates can be used in actual projects, we provide several end-to-end worked-out project examples executed using Vienna. Links to these are provided below:
1. Bike rental prediction (Numerical data) [Link to come]
2. Creating supervised word-embeddings using deep learning (NLP use case with deep learning) [Link to come]
3. Image classification using deep learning (Vision use case with deep learning) [Link to come]
4. Predictive maintenance [Link to come]