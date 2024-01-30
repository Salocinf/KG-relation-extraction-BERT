# Knowledge Graph Relation Extraction with BERT

This is a repository to accompany the master thesis "Relation Prediction from Abstracts in Wikipedia using BERT" submitted by Nicolas Fürhaupter to the Data and Web Science Group, Prof. Dr. Heiko Paulheim at the University of Mannheim.

## Contents

* Rule_Based_Approach.ipynb
  * Data Retrieval for the rule-based approach and both BERT scenarios
  * Creation of dataframes for ML methods
  * Setting the baseline metrics using ML methods
    * Naive Bayes
    * SVM
    * Decision Trees
    * Random Forest
    * XGBoost
    * RIPPER
    * Neural Network

* BERT_Scenario_A.ipynb
  * Implementation of Scenario A
    * Binary classification per entity and relation for nine relations
  * Creation of datasets for nine relations
  * Model creation, training, and testing for Scenario A

* BERT_Scenario_B.ipynb
  * Implementation of Scenario B
    * Multiclass classification for all relations per entity
  * Creation of datasets for all relations within the knowledge Graph
  * Model creation, training, and testing for Scenario B
