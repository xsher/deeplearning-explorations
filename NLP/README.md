# Project
This project is based on a SEMEVAL challenge.
The choice of Challenge is Task 3 with focus on Question-Answering.

### Problem Formulation
In this project, I will be covering Subtask B: Question-Question Similarity.

**Given**

A new question (aka original question) and the set of the first 10 related questions (retrieved by a search engine), rerank the related questions according to their similarity with respect to the original question. In this case, we will consider the "PerfectMatch" and "Relevant" questions both as good (i.e., we will not distinguish between them and we will consider them both "Relevant"), and they should be ranked above the "Irrelevant" questions. The gold labels for this subtask are contained in the RELQ_RELEVANCE2ORGQ field of the XML file. See the README file for a detailed explanation of their meaning. Again, this is not a classification task; it is a ranking task.

**Evaluation**

The official scorer will provide a number of evaluation measures to assess the quality of the output of a system (see the tools page), but the official evaluation measure towards which all systems will be evaluated and ranked is MAP using the 10 ranked questions.

### Objectives
- Applications of different preprocessing methods
  - lemmatize/non-lemmatize
  - POS tags
  - unigram/bigram/skip-gram
- Application of different techniques
  - The objective is to evaluate what is the best way to do the word representations in order to calculate the similarity
  - Examples:
    - Bag-of-words
    - TF-IDF
    - Latent Semantic Indexing
    - Latent Dirichlet Allocation
    - Word2Vec
    - FastText
    - FastText pre-trained
- Application of same technique on different problems
  - Question - Answer
  - Question - Question


### Directory Structure
The codes for the exploration can be found in: `SEMEVAL-Task3-SubtaskB-FINAL.ipynb`

The report and discussions are in: `NLP_report.pdf`
