# Natural Language Processing (CAI2505) - Lab Sheets

This repository contains the practical lab sheets and Jupyter Notebooks for the **Natural Language Processing (CAI2505)** course. 

## Lab Sheets Overview

Below is a breakdown of the lab sheets included in this repository and the specific NLP concepts each one covers:

* **Lab Sheet 1 (1-1 & 1-2): Text Preprocessing & Word Embeddings**
  Covers foundational text cleaning (tokenization, stop-word removal, lemmatization) using NLTK and spaCy, followed by an exploration of word vectors and contextual embeddings using Word2Vec, GloVe, BERT, and RoBERTa.

* **Lab Sheet 2: Complex Word Identification**
  Detects complex or uncommon words in sentences using frequency-based methods and machine learning (Decision Tree Classifier) trained on text corpora.

* **Lab Sheet 3: Sentiment Analysis and Named Entity Recognition (NER)**
  Performs sentiment polarity analysis using TextBlob and extracts named entities using spaCy.

* **Lab Sheet 4: Lexical Simplification**
  Develops a pipeline to simplify complex sentences while preserving meaning, utilizing WordNet for synonym replacement and GloVe embeddings for cosine similarity checks.

* **Lab Sheet 6: Extracting PoS Features**
  Focuses on extracting Part-of-Speech (PoS) tags, analyzing their distribution, and using them as features for a Logistic Regression text classifier.

* **Lab Sheet 7: Building a PoS Tagger**
  Designs and implements custom PoS taggers using three different approaches: Rule-Based (RegexpTagger), Statistical (Hidden Markov Models), and Machine Learning (Logistic Regression).

* **Lab Sheet 8: Title Case Conversion using HMM**
  Models title case conversion as a sequence labeling problem, building a Hidden Markov Model (HMM) and using the Viterbi algorithm to convert lowercase text into proper title case.

* **Lab Sheet 9: Machine Translation using Transformers**
  Implements a transformer-based machine translation model (MarianMT via Hugging Face) to translate English to Hindi and evaluates the output using the BLEU score.

* **Lab Sheet 10: Lexical Candidate Generation and Ranking**
  Generates lexical substitution candidates using Masked Language Modeling (DistilBERT) and ranks their contextual appropriateness and semantic similarity using SentenceTransformers.
