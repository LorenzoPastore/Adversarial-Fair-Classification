<p float="left">
 <img src="https://github.com/LorenzoPastore/University-Works/blob/master/Advanced%20Machine%20Learning/images/DS%20Logo.png" width = "500"/>
 <img src="https://github.com/LorenzoPastore/University-Works/blob/master/Advanced%20Machine%20Learning/images/Bicocca%20Logo.png" width = "100" align="right"/>
</p>

# Adversarial Fair Classification
### A Fair Classifier based on Adversarial Debiasing

<p align="center">
	<img src="https://github.com/LorenzoPastore/University/blob/master/Advanced%20Machine%20Learning/images/fair_HD.gif" width = "300">
</p>

In this repo a binary classification problem on income prediction is developed and analyzed in terms of classification and fairness metrics. A fair classifier based on Adversarial Debiasing is proposed, along with a Hyperparameters Optimization (HPO).


The widespread use of algorithmic decision processes in sensible domains like credit ratings, justice or housing allocations have raised many questions about their transparency, accountability and fairness. Although these complex learning methods are often treated like black boxes, they should be designed in order to ensure minimum discrepancy between the outcomes related to people that share particular sensible attributes (e.g. age, sex or race) and the others.

In this work, the binary classification problem of income prediction has been addressed with respect to group fairness through two sensible attributes: race and sex. First, a baseline neural network classifier was developed and evaluated in terms of classification and fairness metrics.

Once tested and quantified the disparate treatment between protected and unprotected groups, a ”fair” classifier based on Adversarial Debiasing was developed with the aim to maximize the p-rule at the minimum possible accuracy waste. This model was optimized with a Sequential Model Based Optimization (SMBO) approach. Lastly, the performances on classification and fairness metrics were compared between the baseline classifier and the fair classifier.

## Report

[Here](https://github.com/LorenzoPastore/University/blob/master/Advanced%20Machine%20Learning/report.pdf) you can find the technical report with the details of the analysis.

## Presentation

[Here](https://github.com/LorenzoPastore/University/blob/master/Advanced%20Machine%20Learning/AML%20presentazione.pdf) you can find a short presentation.

## Notebook

[Here](https://github.com/LorenzoPastore/University/blob/master/Advanced%20Machine%20Learning/code.ipynb) you can find the notebook.





