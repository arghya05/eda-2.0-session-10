
# Objective

## 1. Implement the following metrics (either on separate models or same, your choice):
- Recall, Precision, and F1 Score
- BLEU
- Perplexity (explain whether you are using bigram, trigram, or something else, what does your PPL score represent?)
- BERTScore



**For this submission, we have prepared the dataset directly as explained in the steps below-**

## Recall, Precision, and F1 Score
Precision quantifies the number of positive class predictions that actually belong to the positive class. Recall quantifies the number of positive class predictions made out of all positive examples in the dataset. F-Measure provides a single score that balances both the concerns of precision and recall in one number

## BLEU
The Bilingual Evaluation Understudy Score, or BLEU for short, is a metric for evaluating a generated sentence to a reference sentence.

A perfect match results in a score of 1.0, whereas a perfect mismatch results in a score of 0.0.

The score was developed for evaluating the predictions made by automatic machine translation systems. It is not perfect, but does offer 5 compelling benefits:

It is quick and inexpensive to calculate.
It is easy to understand.
It is language independent.
It correlates highly with human evaluation.
It has been widely adopted.

## Perplexity
 perplexity metric in NLP is a way to capture the degree of 'uncertainty' a model has in predicting (assigning probabilities to) some text. It is related to Shannon's Entropy. Lower the entropy (uncertainty), lower the perplexity. If a model, which is trained on good blogs and is being evaluated on similarly looking good blogs, assigns higher probability, we say the model has lower perplexity than a model which assigns lower probability.

## BERTScore
BERTScore leverages the pre-trained contextual embeddings from BERT and matches words in candidate and reference sentences by cosine similarity. It has been shown to correlate with human judgment on sentence-level and system-level evaluation.
