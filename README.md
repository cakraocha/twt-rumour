# Rumour Detection and Analysis on COVID-19 Twitter Dataset
*This is a project to complete COMP90042 Natural Language Processing, Semester 1, 2021*<br/>
*Lecturer: Jey Han Lau*

## Task 1 - Rumour Classifier
Given a labeled dataset, build a classifier to detect which tweet belongs to rumour and non-rumour. Each row of the dataset comprised of source and reaction tweets. Only the source tweet will be classified as rumour or non-rumour.

Result summary: Using BERT with preprocessing and maximum matching (word segmentation) algorithm, the model can achieve **87.15%** accuracy on training validation, and **81.87%** F1 Score on Codalab competition.

## Task 2 - COVID-19 Related Twitter Rumour Analysis
The classifier from task 1 will be used on unlabeled COVID-19 related Twitter data from January 2020 - August 2020, with majority of the data between April - June 2020. The dataset contains 17,453 rows with 237,223 total replies.

Result summary: A topic modelling performed yielding 5 different mutual key topics identified. On the rumour side, people tend to talk about `cases, deaths, #bailouthumans, lost, job` where on the non-rumour side people tend to talk about `wear, mask, India, vaccine, fauci`.

For more details, please find in `report/` folder.