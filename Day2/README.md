# Day 2

## Seminar: Extracting Latent Moral Information from Text with ChatGPT
*Speaker: Justin Chun-Ting Ho*

Justin began his talk by discussing the debate around morality. 
Justin pointed out that although people discuss moriality often, they rarely agree on what is the right thing, how to do the right thing, and what is relevant to morality.
Justin introduced two types of moral systems: individualising and binding.

Justin then introduced the moral foundation theory, which states that moral foundations are innate, universal, and intuitative. 
There are five foundations: care/harm, fairness/cheating, loyalty/betrayal, authority/subversion, and sanctity/degradation.

Justin's research is focused on measuring moral foundations from text. 
The fact that no one agrees on morality and what is moral is a major barrier which Justin must consider in his research.

Justin is now investigating if he can use ChatGPT in his research. 
ChatGPT is a large language model (LLM). 
It is trained on a large coprups of text data, and can provide answers to questions in a way that looks similar to text written by humans.
However, ChatGPT does not know the context of words in the same way humans do.

In his research, Justin compared different methods of measuring moral foundation in text:

1. Content analysis
2. Moral foundation dictionary
3. crowdsourced
4. ChatGPT (zero-shot and dictionary assisted)

Justin found that the dictionary-assisted ChatGPT approach seemed to perform similarly to the dictionary approach. 
However, ChatGPT did hallucinate and was possibly unreliable.

## Text Analysis
The practical session on text analysis was led by Jessica Witte. 
Text analysis is the computational evaluation, investigation, and exploration of text data. 
You can use supervised or unsupervised methods for text analysis, and types of text analysis include topic modelling, named entity recognition, sentimment analysis, and text classification.
It is important to remember that the training data used to build the algorithm is important, and computers "read" differently than humans do.

### Text Mining
Text mining is a type of natural language processing which aims to identify patterns and trends  in natural language data.
Methods for text mining include:

- Keyword search / term frequency
- Term frequency-inverse document frequency
- Named entity recognition
- Topic modelling
- Sentiment analysis

### Tokenisation
Tokenisation involves breaking down a piece of text into smaller units called tokens. 
Tokens can be words, sentences, or characters, and can help standardise the text for analysis.

### Text Cleaning
Text cleaning means formatting text fo analysis and removing extraneous information. Common steps include making everything lowercase, removing URLs and symbols, removing stopwors, tokenisation, stemming, and lemmatization.

## Practical 1
We will work with the data scraped from the UK Government and Scottish Government websites yesterday. 
We used the quanteda, quanteda.textplots, quanteda.textmodels, lexicon, tidyverse, and tm R packages.

The sessions aims to:

- Observe the number and length of articles on the cost of living in the last 3 years
- Investigate if there are differentes in the wording about the cost of living between the data sets
