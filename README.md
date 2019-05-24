# NuWCRU README Template (Project Title)

## Project Description
This is a basic template to be included with all NuWCRU github repositories. The purpose of this template is to standardize the metadata generated for each project/analysis so that information can be shared efficiently between personnel. This template should be used as a mere starting point, and can/should be altered to suit the specific needs of each project.

Although this github space will likely be used to host many different projects, much of the work will be conducted in R. For basic workflow techniques within R, Hadley Wickham's freely available [R for Data Science](https://r4ds.had.co.nz/index.html) is highly recommended. See [Chapter 8: Workflow](https://r4ds.had.co.nz/workflow-projects.html) for working with R Projects.


## General Project File Structure
To avoid chaotic project folders, it helps to organize files into a common structure. This is just an example, so keep in mind that the files and their descriptions will be unique to each project.
```
├── .gitignore               <- Files that should be ignored by git. 
|
├── README.md                <- The top-level README including general project descriptions
|
├── data
│   ├── tab_data.csv         <- Converted, but pre-process tab data
│   ├── processed.csv        <- Data ready for modeling
│   ├── raw                  <- Raw data pulled from source
│   └── temp                 <- Temporary files.
│
├── docs                     
│   └── process_doc.md       <- Displaying process and some results (only if needed)
|
|── figures
|   ├── range.png            <- figure description
|   ├── eda.png              <- figure description
|   └── growth.png           <- figure description
|
└── scripts
    ├── d_wrangle.R          <- wrangling pre-processed tab data, output: processed.csv
    ├── src.R                <- cleaned and standardized covariates
    ├── model.R              <- model building/runs
    └── vis.R                <- model results, tables, and visualizations


```

## Data 
  * Description of the data here occurs here. All relevant information needed to understand the data, and subsequently the analysis should be documented. 
  * This includes covariate abbreviations, specific data collection methodology, years data was collected, and possibly even contacts in the case of questions. 
  * If data was pulled from a database, notes about the queries used should be documented here

## Relevant Study Documents
If methods are adopted from others (articles or research groups), links to the original documents can be placed here.

## Authors
Contact information for the most recent personnel working on the project.
