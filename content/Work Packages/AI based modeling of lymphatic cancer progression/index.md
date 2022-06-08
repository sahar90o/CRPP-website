---
title: AI based modeling of lymphatic cancer progression
image: 
  focal_point: "top"
---


<!--more-->

Background: 

To optimally balance the chance of tumor control versus the risk of side effects, local cancer treatment with radiotherapy and surgery rely on accurate definition of the loco-regional extension of the disease on medical images. Most cancers progress through the lymphatic system and form metastases in regional lymph nodes. In this project, we focus on radiotherapy target delineation in head & neck cancer, however, the AI methodology to be developed will be equally applicable to other cancer sites with lymphatic spread. 


Working hypothesis: 


AI methods promise improvements in all steps of head & neck cancer target definition for radiotherapy planning, namely by partially automating target volume delineation, more consistency and less inter-observer variability, and ultimately improvements through more personalized definition of target volumes.



Specific aims for this research project:

1- Automatic segmentation of lymph node levels (blue) and individual lymph nodes in CT images (yellow, green), which is currently a labor-intensive manual task.

2- Improved definition of regional lymph node metastases via better discrimination of healthy and metastatic lymph nodes using radiomic analysis of suspicious lymph nodes (yellow or green).

3- Development of a personalized model for estimation of the microscopic cancer spread using the methodology of Bayesian network and Hidden markov models. This will improve the decision which lymph node levels should be included in the target volume treated with radiation.


Machine learning model of lymphatic cancer progression

We developed a machine learning model of lymphatic tumor progression in head & neck cancer using the methodology of Bayesian networks and Hidden markov models, which is illustrated in figure 2. In this model, each lymph node level is associated with a binary random variable for the microscopic state, which indicates whether or not the level truly harbors tumor including occult metastases. The microscopic state is a latent state that is not directly observable for radiotherapy patients. Associated with the microscopic state is an observable macroscopic state, which indicates whether a lymph node level contains visible metastases based on PET-CT imaging (and possible additional diagnostic modalities). Macroscopic and microscopic states are linked via the specificity and sensitivity of PET-CT imaging. The microscopic states are connected via directed arcs if one lymph node level receives efferent lymphatics from the other. Each arc is associated with a probability of tumors to spread from one level to the next. For example, level II and level III are connected by an arc reflecting the directional lymph flow from level II to level III, which allows tumors to spread from level II further down to level III. Thus, the graph of the Bayesian network reflects the anatomy of the lymphatic drainage system.

The parameters of the model, the probabilities of tumor cells to spread from the primary tumor site to the lymph node levels and in between lymph node levels, can be learned from datasets of lymphatic progression patterns.

A given model can then be used to calculate the probability of microscopic involvement for a newly diagnosed patient. In this application phase, the population based knowledge on lymphatic progression patterns is combined with the individual patient’s state of disease progression, i.e. the location of visible macroscopic metastases.



