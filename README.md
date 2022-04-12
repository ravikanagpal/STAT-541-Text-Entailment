# STAT-541-Text-Entailment


### Team:
|Student name| CCID |
|------------|------|
| Ravika Nagpal | ravika1 |
|Chirag Daryani   |  cdaryani    |
| Rohan Verma  |   rverma3   |
| Karan Chadha  |kchadha1      |


### Task Description:

We are attempting the problem of **Text Entailment**, which is determining whether a piece of text logically follows from another piece of text. It is the task of **Natural Language Inference (NLI)** where given pairs of small text snippets (one or more sentences in English), known as Text-Hypothesis (T-H) pairs, we have to decide if the **hypothesis contradicts, entails or is neutral to the text.** 

In this project , we are performing a quantitative analysis of prevalent models and embeddings for the task of text entailment and we are evaluating which model and embedding is the best for the text entailment task. 

### Description about the Dataset:

For our task, we have used the Stanford Natural Language Inference (SNLI) corpus, which is a collection of 570k human-written English sentence pairs manually labeled for balanced classification with the labels entailment, contradiction, and neutral. 

Table 3 shows a few examples of pairs of sentences picked from the dataset and it’s corresponding entailments. Each entry is a pair of hypothesis and baseline with gold-label, and the parse structure of sentences in Penn Treebank format. Some key statistics about this corpus are listed in Table 2. About 2% of the622

sentence pairs are labeled ’-’ in the corpus due to lack of consensus. These were not included in63
either the training or evaluation process. This results in 549,367 training pairs, 9842 development64
pairs and 9824 test pairs

This complete dataset for the task can be downloaded from [this website](https://nlp.stanford.edu/projects/snli/). 



### Code Files:

* `GLoVe-BOW-all-models.ipynb` : All models built on Bag of Words (BoW) and GLoVe Embeddings.

* `elmo-embedding-all-models.ipynb` : All models (CNN + LSTM + Bi-LSTM) built on ELMo Embeddings.


### References:

