# **Global Water Use and Effects**
## **Introduction and Origin**
#### "The Global Water Use and Effects" repository utilizes data from AQUASTAT, an information system created by the Food and Agriculture Organization of the United Nations that investigates water resources and agricultural management. 
#### The [AQUASTAT Site](https://data.apps.fao.org/aquastat/?lang=en) has several different variables one can access to make large datasets. To create the exact dataset used in this repository, select the following variables: Environment and Health, Water Use, Water Resources, World, and 2020. This repository can be used to find links between water resources, uses, and the resulting impacts around the globe, providing insight into the causes of water scarcity and possible ways to help diminish global dehydration.
## **Contents**
#### The global water use repository contains an original CSV file filled with data provided by AQUASTAT. This data ranges from global water resource usage to water resource impact. Access to this original file can be found with this link: [Original AQUASTAT Data Set](Datasets/AquastatOriginalData.csv)
#### The repository also contains a [CoLab](https://colab.google/) notebook that uses Python coding language to turn the original AQUASTAT dataset into two synthesized subsets used for analysis. Access to this Python notebook can be found with this link: [Python Notebook](PythonNotebook.ipynb)
#### The repository also includes two subsets of the original dataset from AQUASTAT created by the Python notebook. One subset focuses on the global dependency ratio of total renewable water resources and is linked here: [Dependency Ratio Subset](Datasets/dependencyratio.csv) 
#### The other subset focuses on global agricultural water withdrawal and its drain on total renewable resources and is linked here: [Agriculture Water Use Subset](Datasets/agriculturalwater.csv)
## **Data Visualizations**
#### The dependency ratios on renewable water resources differ across the world. In some areas, populations require these resources to have enough water to drink, grow crops, and keep areas clean. The following chart, made through [DataWrapper](https://app.datawrapper.de/select/map), displays the different dependency ratios across the globe. 
#### ![alt-text](Visualizations/DependencyRatioGraph.png)
#### The second subset regarding agricultural management suggests a problem among a few countries struggling with water scarcity and highly dependent on renewable water resources. Countries such as Egypt, Sudan, and Uzbekistan greatly rely on renewable water but use high percentages of their renewable water in agriculture. The following visualization was also created with [DataWrapper](https://app.datawrapper.de/select/map).
#### ![alt-text](Visualizations/AgriculturalWithdrawalGraph.png)
## **Potential**
#### These datasets allow for further analysis of the effect of agricultural practices on water resources and the importance of consistent access to clean water across the globe. These datasets are recent and relevant as they take data from 2020 and include almost every country. Patterns between economy, wealth, and sanitation can all be studied with the help of this repository.
## **Management**
#### This repository was created for an assignment for English 105 at the University of North Carolina with Dr. Gotzler. If a user is having difficulty or wants to get in touch with the creator of the repository, they can use the following email address: lgheflin@unc.edu
