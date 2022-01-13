

![Logo](https://i.ibb.co/QD7zJ3d/integrating.png)


## Repository Structure
* README.md: Project Description
* main.ipynb: Jupyter Notebook with MLflow code example 

## About This Project

This is the companion respository for the Heartbeat article <i>Enhancing MLflow with Comet</i>
by Matt Blasa.  

The contents of this repository is example source code demonstrating Comet's machine learning
and experiment tracking used for MLflow machine learning experiments. 

Click below for the Medium article: 

[![medium](https://img.shields.io/badge/Integrating_Azure_&_Comet-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://heartbeat.comet.ml/integrating-comet-and-azure-databricks-4ec97703a2fe)

## Data 

The data used in this project is taken from the University of Californina Irvine wine quality dataset which can be found here:
https://archive.ics.uci.edu/ml/datasets/wine

## Installation

This project is focused for the Azure Databricks environment. 
To run this project, you will need a Databricks to install Comet library to your cluster, 
and upload the project file. 


<b>Installing Libraries</b>

To get started, select the Install New tab in your cluster:

![Logo](https://cdn-images-1.medium.com/max/640/1*7XSXE1druNLR7afGyeQvJQ.png)

In the Install Library window, select PyPI button. In the package box, type `comet_ml`
If you have a MLflow workflow, I would recommend installing `comet_automl`. Comet_automl
is able to log any existing MLFlow workflow in Databricks. 

![Logo](https://cdn-images-1.medium.com/max/640/1*e_TkO3CyTjb4ks-yBBJjSQ.png)

<br>

<b>Using Project File</b>

<i>NOTE: that Comet API Key has been removed from project file, for privacy reasons. 
You will need to add your experiment API key to use part of this code </i>

![Logo](https://i.ibb.co/QbnQqyR/Import.png)
<br>
<br>
Import will then take you to the import notebooks popup. Either drop the file or click to upload either `Azure-DB-Comet.py`
or `Azure DB-Comet_Jpyter.ipynb` to the notebook.

![Logo](https://i.ibb.co/BC0dyWJ/uploading-file.png)



## 🔗  Project Links

* Diamond Grading Overview: https://www.lumeradiamonds.com/diamond-education/index
* Comet Experiment: https://www.comet.ml/mattblasa/azure-and-comet/view/new
* Comet Documentation: https://www.comet.ml/docs/python-sdk/Experiment/


## Follow Me:
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://blaza.medium.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mblasa/)


