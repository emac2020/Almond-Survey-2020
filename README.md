---
output:
  pdf_document: default
  html_document: default
---
# Almond-Survey-2020-
Analysis of Almond Survey results. This repository contains my survey dataset and analysis of the response data.


## Summary

<describe the purpose of this repository, the information it contains, and any relevant analysis goals. What, why, where, when, how?>

The purpose of this repository is to provide a guideline for the Almond Survey Results and Analyses report. This repository contains the raw survey dataset along with processed datasets that were cleaned for specific analyses.  

The analysis goals of the Almond Survey Results dataset are to examine the relationships between respondent demographics and cover crop adoption. Cover crop is one of several bee-friendly practices that can be implemented on almond orchards to protect and support managed honey bee health. Evaluating factors that may affect cover crop adoption will provide greater insight into the barriers almond producers and farm managers are facing regarding the implementation of bee-friendly practices on their farms. 

The following research questions will inform the analysis goals:

* Where are the respondents' almond orchards located?
* Which demographic factors affect whether or not respondents have planted cover crop in the last 5 years?
* How does region affect whether or not the respondents have planted cover crop in the last 5 years?
* How does respondent role in the almond operation affect whether or not the respondents have planted cover crop in the last 5 years?
* How does respondent age affect whether or not the respondents have planted cover crop in the last 5 years?
* How does the size of the almond operation affect whether or not the respondents have planted cover crop in the last 5 years?


## Investigators

Emily McNamara, Duke University's Nicholas School of the Environment 
Email: emily.mcnamara@duke.edu

## Keywords

*Cover crop: Temporary forage planted between tree rows

*Region: The location of the respondant's almond orchard(s)

*Role in Operation: Respondent could select 'Owner, not responsible for day-to-day management', 'Owner/Operator', or 'Farm Manger (not owner)' to describe the role he or she has in the almond operation. 

## Database Information

This dataset contains response data from a survey that was distributed to almond producers and farm managers throughout California. The survey was launched on December 10th, 2019 and was closed on February 5th, 2020. Data were collected using Qualtrics.


csv files were saved as 'Almond_Survey_Results_raw.csv', 'Almond_Survey_Data_Project_Processed.csv' , and 'Almond_Survey_Numeric_Answers_Processed.csv' 


## Folder structure, file formats, and naming conventions 

<describe the folders contained in the repository, including what type of files they contain>

Data/Processed: This folder contains datasets that were processed from the raw dataset as csv files

Data/Raw: This folder contains the raw survey dataset as a csv file

Output: This folder contains output information from the analyses #????

Code: This folder contains the code used for the analyses


<describe the formats of files for the various purposes contained in the repository>

##What does this ^^ mean??


Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)


## Metadata

### Almond Survey Results Dataset
Column                      | Description
----------------------------| -------------
End Date                    | Date the respondent completed submitted the survey
                            |
Role in Operation           | Respondent's role in operation ('owner, not responsible for                                     | day-to-day management' , 'owner/operator', 'farm manager (not                                   | owner)')
                            |
County                      | County the almond orchard(s) was located (Counties in California)
                            |
Regions                     | Region in which the county was located (Sacramento Valley, Delta,                               | San Joaquin Basin, Tulare Basin)
                            |
Total Yield Bearing Acreage | Total amount of acreage with almonds that are mature enough to                                  | produce nuts (total acres)
                            |
Pollinator Manager          | The person in charge of pollination management decisions (Farm                                  | manager, owner, independent PCA, affiliated PCA, beekeeper,                                     |  beebroker, pesticide applicator)
                            |
Cover Crop Grown            | Whether or not the respondent has grown cover crop in the last 5                                | years (Yes or No)
                            |
Cover Crop Seeds            | Description of how the respondent acquired cover crop seed (Private                             | cost-share program, CCA/PCA/Crop Consultant, Directly from seed                                 |company, Federal cost-share program)
                            |
Cover Crop Satisfaction     | Respondent's level of satisfaction with cover crop (Not satisfied,                              | Somewhat satisfied, Very satisfied)
                            |
Cover Crop Interest         | Respondent's level of interest in planting cover crop if he/she had                             | not grown cover crop in the last 5 years (Yes, No, Not sure)
                            |
Cover Crop Concerns         | Respondent's concerns with planting/maintaining cover crop
                            |
Cover Crop Incentives       | Possible incentives that may assist respondent in planting cover                                | crop
                            |
Water Source                | The water source used to irrigate the respondent's almond                                       | orchard(s) (Groundwater, Surface water, Combination of groundwater                              | and surface water)
                            |
PPH Grown                   | Whether or not the respondent has permanent pollinator habitat                                  | around or near the almond orchard(s) (Yes, No, Not sure)
                            |
PPH Satisfaction            | Respondent's level of satisfaction with permanent pollinator                                    | habitat (Not satisfied,Somewhat satisfied, Very satisfied)
                            |
PPH Interest                | Respondent's level of interest in planting permanent pollinator                                 | habitat if he/she does not have the habitat around or near almond                               | orchard(s) (Yes, No, Not sure)
                            |
PPH Concerns                | Respondent's concerns with planting/maintaining permanent                                       |  pollinator habitat
                            |
PPH Incentives              | Possible incentives that may assist respondent in planting                                      |  permanent pollinator habitat
                            |
Pollination                 | How the respondent pollinated his/her almond orchard in 2019 (Our                               | orchards were not mature enough, We rented all our bees, We rented                              | some bees and supplied some of our own, Prefer not to answer)
                            |
Beekeeper Location          | Where the bee hives came from if the respondent rented honey bees                               | in 2019 (Out of state, Near your orchard, California but not                                    | neighboring county, Prefer not to answer)
                            |
Rental Price                | Highest rental fee/ per bee hive the respondent paid in 2019 ($)
                            |
Age                         | The age range of the respondent

## Scripts and code

<list any software scripts/code contained in the repository and a description of their purpose.>

## Quality assurance/quality control

<describe any relevant QA/QC procedures taken with your data. Some ideas can be found here:>
<https://www.dataone.org/best-practices/develop-quality-assurance-and-quality-control-plan>
<https://www.dataone.org/best-practices/ensure-basic-quality-control>
<https://www.dataone.org/best-practices/communicate-data-quality>
<https://www.dataone.org/best-practices/identify-outliers>
<https://www.dataone.org/best-practices/identify-values-are-estimated>