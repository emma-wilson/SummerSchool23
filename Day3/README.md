# Day 3

## Seminar: Affective partisan sorting in the UK
*Speaker: Ugur Ozdemir*

Affective partisan polarisation (APP) is strong emotional attachments towards co-partisans and hostility towards opposing partisans.
APP can be measured through 'thermometer questions' in surveys, e.g. how much do you like or dislike the political parties.
APP has mainly been investigated in the context of American politics, but more recently APP has been investigated in the UK and Europe.

For two party systems, median distances are usually used to measure APP. 
However, the measurement is more complex in multiparty systems.
Each individual is a K-size vector rather than an single datapoint.

Ugar's work uses APP as a latent variable, and uses all the like/dislike information to construct a unidimensional 'affective partisanship space' (reduce NxK matrix to Nx1 matrix).
Using this method, Ugar has examined the poralisation dynamics of the UK electorate. 
If one single dimention explains everything (e.g. everyone who loves the Conservatives hates Labour), then we can infer polarisation.

Ugur looked at data from the British Election Study Internet Panel, from Feb 2014 - May 2022. 
Sample sizes were around 30,000. 
The questions asked followed the format of 'how much do you like / dislike the following party?'.
The dataset covers 'turbulent times', e.g. Scottish Independence, Brexit, and the COVID-19 pandemic.
This gave Ugur an interesting opportunity to investigate if issue polarisation and affective polarisation are related.

Ugur found that issue polarisation is leading to affective partisan sorting, an turbulent times seemed to sharpen affective partisan divisions.
His future work will investigate different subgroups.

## Sentiment analysis

Jessica Witte let the practical on sentiment analysis.
Sentiment analysis is a form of supervised learning that assigns a polarity score (positive or negative) to textual data.
It's important to consider whether the training dataset matches the data that will be analysed, as micmatches can cause strange results.
It works best on the sentence or paragraph level.
Some limitations include sarcasm and humour.

## Practical 1
We will be looking at data scraped from the Reddit subreddits r/AskUK and r/Scotland. 
We will be using the syuzhet, vader, wordcloud, and tm R packages.

The aims for the session are:

- Identify if there are trends that we can observe about sentiment about the CoL in each data set
- Based on one data set only, can we work out of the CoL crisis getting better or worse in 2023? How do things differ in Scotland vs. the UK?

## Data wrangling
Andrew Mclean led the practical on data wrangling. 
Data is often mislabelled or unorganised.
Data wrangling and tidying is simply the process of organising this data.
The aim is to make the data more computer friendly.
This isn't always the same as human friendly data.

With tidy data:

- Every column is a variable
- Every row is an observation
- Every cell is a single value

Good practice is to:

- Have a separate R project for each analysis
- Keep data, scripts and associated files somewhere in the working directory
- Save outputs in a separate folder in the working directory

## Practical 2
We will be processing data for analysis. We will be using the tidyverse package.

The aims for the session are:

- Making sure we get the data on a stage that can make them usable for the analysis 
- Making sure our data to satisfy the FAIR principles so you should never edit your raw data and all the pre- processing that can happen via R is better. This will make sure that if someone else wants to reproduce your steps they will be able to do so
