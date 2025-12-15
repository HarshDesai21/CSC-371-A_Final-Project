# Model card for "Jack/Harsh - Video Game Gender Classification - CSC 371 Final"

Template sourced from (https://github.com/fau-masters-collected-works-cgarbin).

Jump to section:

- [Model details](#model-details)
- [Intended use](#intended-use)
- [Factors](#factors)
- [Metrics](#metrics)
- [Evaluation data](#evaluation-data)
- [Ethical considerations](#ethical-considerations)
- [Caveats and recommendations](#caveats-and-recommendations)

## Model details

_Basic information about the model._

- Person or organization developing model
- Created December, 2025
- Classification Models
- Random Forest Decision Trees, K-Nearest Neighbors, AdaBoost, LinearSVM, SVM RBF
- Paper detailing results and methods attached in repository
- Contact jaschwanewede@davidson.edu, hadesai@davidson.edu for questions.

## Intended use

_Use cases that were envisioned during development._

- The use of these models are to predict the gender of video game characters
- Our goal is to determine whether gender bias in MOBA character design exists, and if ML models can predict gender of characters because of this

## Factors

- The data used in this project are fictional, video game characters, but the goal is to highlight actual inequalities or biases in development

## Metrics

### Model performance measures

- We measured results using model accuracy, F1 scores, precision, and recall.

## Evaluation data

- Data was scraped from several online cites, such as Fandom.com and League of Legends Wiki.
- Further citations found in the paper.


### Motivation

- Are there gender biases in video game character design? If so, can ML classification models be used to predict / discriminate between male and female characters?
- This work aims to highlight design bias in video game character creation. 

### Preprocessing

- Data was cleaned and manually filled in using Excel / Google Sheets from online sources. Additional preprocessing can be found in the MOBA_preprocessing.ipynb file, doing initial analyses and more cleaning.

## Ethical considerations

- The video game industry and community is stereotypically a masculine space, where women and minorities may have experienced discrimination or harassment. This can carry over to developers as well, where character designs and stats may be different depending on the gender of the character. This work aims to highlight these biases, and not further contribute to them, offering an approach to analyze gender differences in video game characters by attempting to distinguish and predict them

### Data

- Data came from online sources, as described in the paper.

### Risks and harms

- No known risks and harms. 

## Caveats and recommendations

- This is a novel approach, and needs further testing with a larger and more balanced dataset. 
- We also recommend additional analyses beyond ML to test the hypotheses of interest, as combining different approaches alongside classification would improve anaylsis (e.g. qualitative content analysis on top of quantitative approach)


