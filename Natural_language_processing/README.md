## To train a model to automatically detect negative reviews for classic movie enthusiasts

**This project shows:**
- ability to loaded and pre-processed text data for vectorization.
- ability to transform text data to vectors.
- ability to defined, trained, and tested models
- ability to reach metric threshold
- ability to arrange the code cells in the order of their execution.
- ability to execute the code cells without errors.
- ability to avoid code duplication
- ability to make conclusions.

**The project involves:**
- Loading  the data.
- Preprocessing the data.
- Conducting an EDA and making conclusion on the class imbalance.
- Preprocessing the data for modeling.
- Training at least three different models for the given train dataset.
- Testing the models for the given test dataset.
- Composing own reviews and classifying them with all the models.
- Checking for differences between the testing results of models in the above two points.
- Presenting the findings.

## Data Description
- *review:* the review text
- *pos:* the target, '0' for negative and '1' for positive
- *ds_part:* 'train'/'test' for the train/test part of dataset, correspondingly

## Task
The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. We'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. It will need to reach an F1 score of at least 0.85.

## Libraries Used
_pandas, numpy, matplotlib, spacy, seaborn, tqdm, sklearn.linear_model, TfidfVectorizer, sklearn.model_selection, sklearn.metricssklearn.metrics, nltk.corpus_
