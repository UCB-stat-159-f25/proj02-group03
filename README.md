[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7TPcE591)
# Project 2: Reproducibility in Natural Language Processing
By: Sofia, Peter, Harish, & Neha

Template repository for Project 2, Stat 159/259 Fall 2025

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UCB-stat-159-f25/proj02-group03.git/HEAD?urlpath=%2Fdoc%2Ftree%2FREADME.md)

## Project Aim
The following summarizes the learning objectives present in `project-description.md`:
In this project, we'll explore modern NLP pipelines designed for text analysis. We'll begin by loading, cleaning, and efficiently pre-processing text using spaCy, mastering core concepts like tokens, lemmas, and stop words to prepare data for downstream analysis. Next, we'll conduct core analysis by using spaCy to extract linguistic features (like lemmas, for example) and perform frequency and temporal analyses to compare language across different documents and historical periods. Finally, this project culminates in building and comparing topic models, where we'll apply both traditional TF-IDF vectorization and LDA to find word co-occurrence topics, and more modern BERTopic (using transformer embeddings) to discover conceptually coherent topics.

## Outlining Process in Each Section
### Part 1
In this section on the `nlp-P01.ipynb` file, we'll be conducting exploratory data analysis on the State of the Union (sou) speeches data set since our first president. We have created bar charts, line plots, and other visualizations to get an intermediary distribution of the variables in this dataset. For each of these visualizations, we'll also provide commentary on our thoughts, findings, and learnings.

### Part 2
In this notebook, `nlp-P02.ipynb`, we'll be performing simple text processing and analysis using the SpaCy library on the `SOTU.csv` file. The data is structured as a CSV, featuring columns for the president's name, the full speech text, the year of the address, and the speech's word count. While the main SpaCy package should already be included in your `environment.yml` setup, we'll also need to explicitly download the en_core_web_sm English language text processing model to complete our analysis.

### Part 3
In this notebook, `nlp-P03.ipynb`, we will compare two methods for creating topic models of the speeches we've been analyzing: Latent Dirichlet allocation (LDA) and BERTopic.

### Part 4

For this section, in the `nlp-P04.ipynb`, we built on the BERTopic model to explore the topics over time to understand which are more popular or less. We also worked on hierarchical topic modeling, where we applied a clustering model to group similar topics.
