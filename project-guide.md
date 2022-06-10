<img src="images/nyplogo.png" alt="nyplogo" width="400"/>

# ITI105 Machine Learning Project

## Module Objective

In this module, you will apply the knowledge and skills  acquired in other PDC1 modules to develop a solution for a problem in selected domain using machine learning approach.

## Module Learning Outcomes
1. Identify and select a suitable machine learning model for a given problem and data set
2. Develop and deploy a machine learning application using appropriate software framework and tools
3. Apply model tuning and optimization to improve performance of machine learning systems
4. Evaluate machine learning models using appropriate metrics for efficiency and effectiveness

## Project Team

You are expected to form a project team of maximum 3 members. 

Each member should be able to complete the associated tasks independently. Marks will be deducted for individuals who rely heavily on others to complete their tasks. If you have any concerns working with one of your project teammates, please fill out the optional [teammate evaluation form](https://forms.gle/1UEj6XgwDNS2Cono8) (only seen by the teaching staff). Please do not wait until last minute to raise your concerns. 

The role of project mentor is to provide guidance to the team on your proposal, and to make sure you are on the right track in your milestones and final presentation and report. 

Please fill up the [online form](https://forms.gle/dH4ijpy5xqNsbnhx8) of your project team members.

## Deliverables and Assessment Components

This project consists of the following assessment components:

|Assessment components|Group|Individual|Total|
|----|---|---|---|
|Project Proposal|15%||15%|
|Milestones||25%|25%|
|Final Presentation|10%|20%|30%|
|Final Report|5%|25%|25%|

## Project Proposal

In the project proposal, your team will pick a problem from the given **[list of projects](./project-list.md)**, formulating it as a machine learning problem to work on early and receive feedback from project mentors.

Once you have identified the problem, it can be useful to research on some prior work or research on the related topics. Another important aspect of your project is to identify one or several datasets suitable for your chosen problem. If that data needs considerable pre-processing  to suit your task, or that you intend to collect the needed data yourself, bear in mind that data collection is only one part of the entire project scope, but can often take up sizeable amount of time. You are still expected to have solid methodology and discussion of results, so pace your project accordingly.

Your project proposal should include the following information:

- Formulation[[1\]](#_ftn1): Is the problem suited for a ML solution? What is the alternative? Any heuristic you can use?  What are the appropriate success metrics? How do you frame it as machine learning problem? What are the suitable metrics to use for your model? 
- Dataset: What kind of data you need and how do you plan to collect them? •      ? If it is some existing dataset (e.g., from Kaggle), include reference link to the dataset and provide some discussion how the data was collected by the author/contributor of the dataset. How relevant is this dataset to your chosen problem?
- Methods: What kind of ML approach (e.g., supervised/unsupervised or others) are you planning to use? 
- Deployment: How do you intend to use the model? Provide an overview of how the model is used in the overall solution. You can illustrate this with a system architecture diagram. 

#### Grading Rubrics
|                    | Need Improvement                                             | Satisfactory                                                 | Good                                                         | Excellent                                                    |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| *Project Proposal* | <ul><li>No or minimal formulation of the problem. </li><li>No reference to dataset is provided or dataset given is not relevant to the problem. </li><li>No ML approach is provided or incorrect approach proposed for the problem</li><li>No deployment scenario provided or lack of details on deployment </li></ul><br/>(< 6 marks) | <ul><li>Some problem formulation is provided.</li><li>Dataset mentioned is somewhat relevant to the problem.</li><li>Appropriate ML approach is provided</li><li>Some discussion on how the model is to be deployed. </li></ul><br/>(< 10 marks) | <ul><li>Clear problem formulation but miss out certain details or consideration</li><li>Dataset is relevant to the problem</li><li>Clear discussion on how the model is to be deployed in the overall solution.</li><ul/><br/> (< 13 marks) | <ul><li>Clear problem formulation with consideration for alternative solution.</li><li>Dataset is relevant with discussion on how the dataset is collected. </li><li>	Correct ML approach proposed with some discussion on other ML approaches. </li><li>Clear and detailed discussion on how the model is deployed in the overall solution.</li></ul><br/>(< 15 marks) |

## Milestones
The milestone report should focus on data understanding and analysis. You should include a brief description of the dataset chosen. You should also describe any data preprocessing/transformation that is required for feature extraction, and any feature engineering done. Each member can use the same dataset or different datasets if the team has not decided on which dataset to use. If you are collecting your own data, you should also describe your data collection methodology, and any limitation with the data collected. 

The milestone report should be submitted individually in the form of Jupyter notebook, with documentation in markdown cells.  

### Grading Rubrics

The milestone is mostly intended to get feedback from project mentors to make sure you’re making reasonable progress. As long as your milestone follows the instructions above and you seem to have tested any assumptions which might prevent your team from completing the project, you should do well on the milestone.

|                                                              | **Need Improvement**                                         | **Satisfactory**                                             | **Good**                                                     | **Excellent**                                                |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| *Data collection,* *data exploration, data preparation and feature engineering (Individual)* | <ul><li>No description or unclear description of dataset used</li><li>No or minimal data exploration done</li><li>No or minimal data preparation</li><li>Codes are not organized</li></ul><br/>(< 10 marks) | <ul><li>Somewhat clear description of the dataset used</li><li>Some data visualization is performed or some description of the data characteristics</li><li>Some basic data preparation is done</li><li> Codes are somewhat organized</li></ul><br/> (< 15 marks) | <ul><li>Clear description of dataset provided</li><li>Significant amount of data exploration done with accompanying discussion</li><li>Significant amount of data preparation done with some discussion</li><li>Some attempts at feature engineering</li><li>Codes are well-organized</li></ul><br/>(< 20 marks) | <ul><li>Clear description of dataset with some insights provided</li><li>Significant amount of data exploration done with very insightful discussion</li><li>Significant amount of data preparation done with very insightful discussion</li><li>Significant amount of feature engineering done</li><li>·    Codes are well-organized</li><li>Significant effort in doing data collection</li><br/>(<= 25 marks) |



### Dataset

While we do not expect you to have to spend too much time collecting raw data, the process of inspecting and visualizing the data, trying out different types of preprocessing, and doing error analysis is often an important part of machine learning. Hence if you choose to use pre-prepared datasets (e.g., from Kaggle, the UCI machine learning repository, Google Datasets.) you are still required to do some data exploration and analysis to get familiar with the problem.  



## Final Report

Final project report should not be more than 15 pages, excluding references. It should include the following sections: 

- ML Formulation
  - Here you can briefly describe the ML framing of the problem. Clearly state what the input and output is, and the kind of ML model used (e.g., regression, classifier, etc.). 

- Data Preparation & Feature Engineering
  - Here you should describe the final prepared data and final feature set used for your modeling. Unlike your milestone report, you do not need to show any data understanding/visualization and different transformation and feature engineering you have tried.  You can refer to your Milestone report to extract relevant information and put in here.

- Modelling and Experiments
  - Here you can describe the different models (and corresponding feature set) you have experimented with. This should not be a listing of experiments (and its associated results) you have tried. The listing should be in the experimental logs, see the section on experimental log). The report should focus on what is your hypothesis, what model you are using to test the hypothesis, error analysis, observations, and performance tuning. 
  - As a team, each member may conduct different experimentations using different algorithms. Each member can describe their experimentations in different subsection and clearly stated the name of the member.
- Deployment / Application
  - If you have deployed your model either as part of an application or a web service, describe the deployment/application here. Include the application architecture, technology stack you used, and other relevant details.

### Experimental Log
You need to maintain an experimental log (as an excel file) that captures ALL the experiments you have run (e.g., the different experimental parameters you have tried, the results). This log will be helpful for you to understand what works and what does not. It also helps us to verify your work. It is not enough to just mention that you have tried MANY different models but cannot provide any discussion/proof on any of the tried models.

### Code
Please include a zip file or preferably a link to a Github repository with the code for your final project. You do not have to include the data or additional libraries (so if you submit a zip file, it should not exceed 5MB).

### Grading Rubrics
|                                                              | **Need Improvement**                                         | Satisfactory                                                 | Good                                                         | Excellent                                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| *ML Framing, Data Preparation, and Feature Engineering* (Group) | <ul><li>Incorrect or missing ML  formulation</li><li>Minimal discussion of final prepared data and features</li></ul><br/>(< 3 marks) | <ul><li>Some writeup on ML formulation</li><li>Some discussion for final prepared data and features </li></ul><br/> ( < 5 marks) | <ul><li>Mostly complete writeup on ML formulation</li><li>Mostly complete discussion of final prepared data and features</li></ul><br/> (< 8 marks) | <ul><li>Very clear ML formulation </li><li>Very clear discussion of final prepared data and features </li></ul><br/>( <= 10 marks) |
| *Modeling and Deployment  (Individual)*                      | <ul><li>Minimal or no experimentation with different models </li><li>Minimal or no discussion of experimental results</li><li> codes are disorganized</li><li>No experimental log attached</li><li>No deployment</li></ul><br/>( < 6 marks) | <ul><li>Some experimentations of different models are shown</li><li>Some discussion of experimental results but lacking in error analysis and minimal model tuning</li><li>Codes are somewhat organized</li><li>Some experimental log attached</li><li>·    Some attempt to deploy</li></ul><br/>( < 13 marks) | <ul><li>Good amount of experimentation is demonstrated.</li><li>Discussion of experimental results demonstrated good understanding of the ML concepts</li><li>Some error analysis is done </li><li>Some model tuning is done. </li><li>Codes are well organized</li><li>Complete experimental log attached</li><li><li>Simple deployment as a web service with simple demo</li></ul><br/>( < 17 marks) | <ul><li>Significant amount of experimentation is demonstrated</li><li>Discussion of experimental results demonstrated good insight and deep understanding of ML concepts</li><li>Significant amount of error analysis is performed and used to improve model performance</li><li>Codes are well-organized with good programming practice</li><li>Complete experimental log attached</li><li>Complete application that use the model</li></ul><br/>(<= 20 marks) |




## Final Presentation

During final presentation, you will be jointly assessed by more than one supervisor to ensure fairness in assessment. Among other things, you are required to show and explain the work you have done. You will be assessed based on your demonstrated understanding of the methodologies used and discussion of the experimental results.

### Grading Rubrics

|                                        | **Need Improvement**                                         | **Satisfactory**                                             | **Good**                                                     | **Excellent**                                                |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| *Presentation (Individual) (30 marks)* | <ul><li>Unable to present the content or incoherent presentation</li><li>Unable to answer most of the questions</li></ul><br/>(< 8 marks) | <ul><li>Somewhat clear and coherent presentation</li><li>Able to answer some questions </li></ul><br/>(< 15 marks) | <ul><li>Mostly clear and coherent presentation with some demo of deployment / application </li><li>Able to answer most of the questions</li><br/>(< 20 marks) | <ul><li>Very clear and coherent presentation with demo of application / deployment</li><li>Able to answer all or most of the questions confidently</li><br/>( <= 30 marks) |



## Project mentors

The project teams will be jointly supervised by a group of project mentors. The project mentors and the contact info are listed below.

|Name|Email|Phone|
|---|---|---|
|Mr. Mar Kheng Kok|mar_kheng_kok@nyp.edu.sg|6550-1647|
|Mr. Lee Ching Yuh |lee_ching_yuh@nyp.edu.sg   | 6550-1620 |
|Mr. Law Chee Yong| law_chee_yong@nyp.edu.sg  | 6550-1650 |
|Dr. Zhao Zhiqiang |zhao_zhiqiang@nyp.edu.sg  |6550-0921 |
|Mr. Wee Chee Hong|wee_chee_hong@nyp.edu.sg   | 6550-1754|
|Ms. Jasmine Ng   |jasmine_ng@nyp.edu.sg   |6550-1763|
|Mr. Tin Aung Win|tin_aung_win@nyp.edu.sg   | 6550-1752 |

## Project Schedule

|Week|Monday|Wed|Thur|
|---|---|---|---|
|13|  | **13-Jul-22**<br/> Project Initiation /Discussion <br/> (MKK-LeeCY) ||
|14|  | **20-Jul-22**<br/> Project Discussion - Project Proposal Submission <br/> (TAW-LeeCY) ||
|15|  | **27-Jul-22**<br/> Project Dev / Consultation <br/> (WCH-KLR) ||
|16|  | **3-Aug-22**<br/> Project Dev / Consultation <br/> (WCH-KLR) ||
|17|  | **10-Aug-22**<br/> Project Dev/ Consultation -Milestone Submission <br/> (MKK-KLR) ||
|18|**15-Aug-22**<br/> Project Dev / Consultation <br/> (ZZQ-LCY)|**17-Aug-21**<br/> Project Dev / Consultation <br/> (TAW-LCY)|**18-Aug-22**<br/> Project Dev / Consultation (Zoom)<br/> (ZZQ-WCH)|
|19|**22-Aug-22**<br/> Project Dev / Consultation (Zoom)<br/> (MKK-LCY)|**24-Aug-22**<br/> Project Presentation (F2F) <br/> (ALL)| |

**Legends* (Zoom)*

- ALL - All tutors
- MKK - Mr. Mar Kheng Kok
- LCY - Mr. Law Chee Yong
- WCH - Mr. Wee Chee Hong
- KLR - Mr. Kee Li-Ren
- TAW - Mr. Tin Aung Win
- LeeCY - Mr. Lee Ching Yuh
- ZZQ - Dr. Zhao Zhiqiang



[[1\]](#_ftnref1) Refer to the lecture notes on ML framing 
