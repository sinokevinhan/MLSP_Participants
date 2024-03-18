# MLSP_Participants

tl;dr
 - Make a PR for a folder with your outputs. Max 2 runs per file.
 - Include a completed metadata form in your submission
 - See dummy folders for an example

## Introduction 

This repository is for shared task participants to upload their system outputs.

To submit your system outputs you should create a new pull request containing a single folder with the same name as your team name. Inside this folder you should submit all the output files that you wish to be evaluated. Alternatively, if you are not comfortable using GitHub, please email your task submission directly to: M.Shardlow@mmu.ac.uk

** All submissions must be uploaded before the extended deadline of *Tues 26th March 11.59pm UTC+0* **

The test files are currently released without labels at: [MLSP_Data/Test](https://github.com/MLSP2024/MLSP_Data/tree/main/Data/Test)

## Participant Metadata

Please fill in the Participant metadata form. By submitting a run for evaluation you are commiting to help with the human evaluation which will take place between Weds 27th March and Fri April 19th. This will involve making judgments on system outputs for a language in which you are proficient for a maximum of 300 instances. We will only evaluate the top systems for a subset of annotations, languages and top-systems depending on annotator availability.

You are also invited to submit a 4-page system description paper to the BEA workshop as specified in the CfP. We have asked for a brief description of your system in the metadata to help us write the task findings paper.

Participants that submit a system description paper should also be willing to review one other task participant paper in the period April 12th - April 19th.

## Submission Format

Task participants are welcome to submit as many or as few of the files found in MLSP_Data/Test for evaluation. Please note that the 'All' folder contains the same instances as in the language specific sub-folders. This is for the convenienc of those participating in all languages. If you wish to only participate in one, or a subset of languages, then please submit the language specific file for those languages.

Participants must submit files with labels following the format shown in [MLSP_Data/Trial](https://github.com/MLSP2024/MLSP_Data/tree/main/Data/Trial).

Participants may submit up to 2 runs per file marked as: _1 and _2 (see dummy2 for an example)

---

For LCP files the data currently has the following fields:

`ID<TAB>Language<TAB>Context<TAB>Token`

Participant systems should add an additional column containing the LCP predictions:

`ID<TAB>Language<TAB>Context<TAB>Token<TAB>Complexity`

---

For LS files the data currently has the following fields:

`Context<TAB>Token`

Participant systems should add further additional columns containing lexical simplification suggestions. Systems can return as many or as few suggestions as they deem necessary for simplification. We will only evaluate up to the first 10 suggested predictions as in the previous LS Shared task.

`Context<TAB>Token<TAB>Suggestion_1<TAB>Suggestion_2<TAB>...<TAB>Suggestion_10`

## Dummy Submission Files

Two dummy submission folders are available to indicate the intended format only. The LCP values and suggestions are randomised in each of these. 

 - The first dummy submission folder (dummy1) contains an example of submitting an all file for both tasks. This participant has only submitted a single run in each case.
 - The second (dummy2) has submitted language specific files. In some instances they have also submitted 2 runs per file.
 
Both are acceptable routes to submission and will be accepted as part of the task.
