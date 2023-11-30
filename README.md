# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2023

+ Team #3
+ Project title: Machine Learning Fairness
+ Team members
	+ Shreya Verma (sv2631)
	+ Lia Cho (lc3683)
	+ Chencan Zou (cz2675)
	+ Jason Cho (yc4076)
	+ Jianjie Sun (js6412)
  	+ Zhaolin Wang (zw2869)
+ Project summary: Recreating algorithms from two different academic papers to compare LFR, LM and LPS algorithms for their ability to predict if a criminal defendant’s likelihood to re-offend, based on prison inmates data from Broward County, Florida from 2013 and 2014 ([Compas data](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)). The academic papers are [Handling Conditional Discrimmination](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6137304) referenced as paper A6, and [Learning Fair Representation](http://proceedings.mlr.press/v28/zemel13.html) referenced as paper A1. Both these algorithms use classification tasks for prediction of the criminal defendant's likelihood to re-offend, and we assess and compare the algorithms looking at their methods and accuracy. 
	
**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

ZW and JS embarked on implementing the algorithm from the paper "A6: Handling Conditional Discrimination (LM and LPS)." Initially, they imported the dataset and rigorously followed standard procedures for data cleaning and preparation, ensuring the dataset was primed for analysis. They then divided this curated dataset into distinct training and testing subsets. Working collaboratively, ZW and JS replicated the core methodologies of Local Massaging (LM) and Local Preferential Sampling (LPS) as outlined in the A6 paper. They developed functions for both LM and LPS, applying these methods to the training data to address potential biases. After integrating these algorithms, they proceeded to train a logistic regression model, evaluating its performance in terms of accuracy and fairness on the test data, with the goal of assessing and comparing the effectiveness of the LM and LPS approaches in mitigating conditional discrimination.

SV and JC began by importing the data and following an official data wrangling and cleaning guide to ensure data readiness for analysis. Subsequently, they partitioned the prepared data into training and test sets. Then, collectively, SV and JC coded the "A1: Learning Fair Representations" paper's formulas and created functions for loss calculation. Finally, they computed accuracy and runtime on the test data, intending to compare these metrics with the A6 results.

CZ has completed the writing of two reports, including "A1: Learning Fair Representations" and "A6: Handling Conditional Discrimination (LM and LPS)." These reports cover the introduction, analysis, and conclusion sections according to the output of the code. LC compiled the results and analysis into making the presentation slide deck, and JC reviewed and edited on the presentation deck. LC organized the files in the github repository and wrote up the readme files for the appropriate folders. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
