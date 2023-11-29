# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2023

+ Team #3
+ Project title: Machine Learning Fairness
+ Team members
	+ Shreya Varma (sv2631)
	+ Lia Cho (lc3683)
	+ Chencan Zou (cz2675)
	+ Jason Cho (yc4076)
	+ Jianjie Sun (js6412)
  	+ Zhaolin Wang (zw2869)
+ Project summary: Recreating algorithms from two different academic papers to compare LFR, LM and LPS algorithms for their ability to predict if a criminal defendant’s likelihood to re-offend, based on prison inmates data from Broward County, Florida from 2013 and 2014 ([Compas data](https://www.propublica.org/datastore/dataset/compas-recidivism-risk-score-data-and-analysis)). The academic papers are [Handling Conditional Discrimmination](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6137304) referenced as paper A6, and [Learning Fair Representation](http://proceedings.mlr.press/v28/zemel13.html) referenced as paper A1. Both these algorithms use classification tasks for prediction of the criminal defendant's likelihood to re-offend, and we assess and compare the algorithms looking at their methods and accuracy. 
	
**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

SV and JC worked on replicating the algorithm from the paper, (A1) Learning fair representations (LFR). ZW and JS worked on replicating the algorithm from the paper, (A6) Handling Conditional Discrimination (LM and LPS). LC and CZ worked on the report and LC and JC worked on the presentation. LC worked on the github organization and readme file.

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
