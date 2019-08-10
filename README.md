# w210_FakeNews:

AUTHORS: Daniel Lee, Hawina Bulcha, James Kajdasz

We are a group of students from the MIDS program at UC Berkeley interested in investigating methods for intervening against Fake news. This repository contains our code and visualization of results, where as our findings are summarized in the website below.
https://catchupcall.wixsite.com/testing

PROBLEM DESCRIPTION:


FILE STRUCTURE AND DESCRIPTIONS

data
| CleanExpData.csv: Cleansed Version of Raw Data from Survey 

| PayData.csv: Pay Data for Subjects

| Spot_Fake_News_July_28,2019_13.40.csv: Raw Experiment Data 

| Survey_Humans.csv: Data Reformatted for Visualization

Models 
| LSTM_Model.ipynb: Multiclass Classification using Randomly Initialized Embeddings and an LSTM Neural Net 

| ELMO_Model.ipynb: Multiclass Classification using Randomly Initialized Elmo Net 

| BERT_Model.ipynb:  Multiclass Classification using Bert 

| Predictions_Using_Elmo_Model.ipynb: Notebook with code for running predictions on 

EDA 
| FNC_InitialDataLook.ipynb: Instructions on how to download the data set. Displays a subset of the data for an initial look.

| Random Subset + EDA.ipynb: Create 10% random subset of fake news articles and perform initial analysis 

FakeNewsSurvey
| Protocol.docx: Updated protocol description CAO 28 July

| data/Spot Fake News_July 28, 2019_13.co.csv: Raw data from Qualtrics

| FakeNewsExperiment.ipynb: Notebook for analyzing Qualtircs results

| Confusion_Matrix_Humans:  

| Tableau Viz of Fake News Survey

| | Data Sources 

| | | CleanExpData.hyper

| | | Survey_Humans.csv (Multiple Connections).hyper

| | | Survey_Humans.hyper

| | Multiclass Detection of Fake News.twb 
