# IHS-NLP-Data-Hackathon
This repository is for data distribution for IEEE COVID-19 NLP Challenge: https://healthcaresummit.ieee.org/data-hackathon/ieee-covid-19-nlp-challenge/
This data hackathon takes place at the IEEE-wide Healthcare Summit in October, 2021: https://healthcaresummit.ieee.org/

## Data Description
Researchers at the Brookhaven Nation Laboratory (BNL), Computational Science Initiative (CSI), and the Oak Ridge National Laboratory (ORNL), Biophysics group, have collected a question-answer dataset annotated by a biomedical domain expert to evaluate the system on specialized information acquisition for protein-related questions.
The BNL-curated QA validation/test datasets that will be provided to the participants will include 113 question/answer pairs for the following four questions:

1.	What are the oligomeric states of coronavirus structural proteins?
2.	What are the oligomeric states of non-structural coronavirus proteins?
3.	What are the catalytic domains (active sites) of coronavirus proteins?
4.	Are there antivirals that target structural viral proteins?

The answers are sentences from papers related to COVID and are labeled as one of the three categories (relevant, partially relevant, and not relevant). 

## Datasets
* Annotated articles: pre-processed JSON files of original PDF articles used for the QA data generation. 
* Validation data: three aligned files - question, sentence, label (i.e., the first label is for the first line of question and sentence.)
* Test data: two aligned files - question, sentence

Due to the limited size of the collected QA data for training a full-fledged NLP model, we recommend that participants leverage external resources to pre-train and fine-tune their models.
There is a list of some available resources in the challenge site.

## Model evaluation
Please refer to the site below for the detailed information about evaluation.
https://healthcaresummit.ieee.org/data-hackathon/ieee-covid-19-nlp-challenge/
