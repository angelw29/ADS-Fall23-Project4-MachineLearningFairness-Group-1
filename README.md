# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

![screenshot](lib/Machine_learning_def_.png)

Term: Fall 2023

+ Team #1
+ Projec title: Implementing Learning Fair Representations (LFR) and Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment (DM and DM-sen) in Python
+ Team members
	+ Angel Wang
	+ Arnulfo Andres Trevino
	+ Mansi Singh
	+ Miao Zhang
	+ Nashita Rahman
+ Project summary: We were tasked with A1 and A4. Task A1 focused on implementing the Learning Fair Representations (LFR) algorithm from Zemel et al. (2013). LFR is a machine learning technique designed to reduce bias in predictive modeling. This project involved developing a Python notebook that allowed us to apply LFR to the COMPAS Recidivism Risk Score Data and Analysis dataset. The primary goal of the algorithm is to enhance the fairness of models by ensuring they do not perpetuate or exacerbate biases present in the training data. This implementation involved cleaning/preprocessing the data, coding the given LFR algorithm, and testing its effectiveness on the given dataset. A4 aimed to develop a Python-based solution for advanced fairness in machine learning models by implementing the principles of DM (Disparate Mistreatment) and DM-sen (Disparate Mistreatment considering sensitive attributes), which go beyond traditional approaches like disparate treatment and disparate impact. The goal was to create algorithms that ensure fairness in classification tasks by minimizing bias not just in treatment and impact but also in the errors (mistreatments) the model makes.
	
**Contribution statement**: All team members approve our work presented in this GitHub repository including this contributions statement. Angel Wang and Nashita Rahman contributed to the construction of Algorithm 1, while Miao Zhang and Mansi Singh contributed to the development of Algorithm 4.
- Angel contributed preprocessing the data (data cleaning)
- Mainly Angel contributed to the construction of Algorithm 1, and Nashita made some minor changes
- Miao contributed to the construction of Algorithm 4
- Miao and Angel helped to prepare the slide for presentation
- Arnulfo made the presentation 

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
