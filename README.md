# Introduction
This is an open-source dataset for deep learning projects, which consists of over 10000 projects and 20000 models collected by us. We gather comprehensive information of each project including the star, fork, watch, issues, and the whole repository itself. 
With this dataset, developers could analyze the potential relationship among the different deep learning projects.

# Structure of the dataset

Name｜Type｜Description｜Items #  

Paper basic database ｜ Json file ｜We use arxiv id of each paper as the main key
in this database. ｜3038

Pro ject basic database ｜ Json file ｜ We use repository URL of each GitHub project as the main key in this database. ｜ 11644  

Pro ject folder info database ｜ Json file ｜ This file consists of the file count in each project. ｜ 11644  

Project model file database (extend version) ｜ Json file ｜ This file has two extra attributes of file
paths tree and readme files info. ｜ 11644  

Project model file database ｜ Json file ｜ This file provides the relationship between project and model files by the only filename. ｜ 11644  

Model feature files database ｜ folder ｜ In this folder, we save all the decoded model files. ｜ 43216  

Model feature files database (filtered) ｜ folder ｜ We filter the model files which are less than one edge. ｜20220

* As github limit the single file to 25MB， some large files can not be uploaded. if you need the full dataset, please contact us.
