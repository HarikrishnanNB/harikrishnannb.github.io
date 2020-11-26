# Chaos based Machine Learning

-------------------------------------------------------------------------------------
## Chaosnet: A chaos based artificial neural network architecture for classification
-------------------------------------------------------------------------------------
### Collaborators: [Snehanshu Saha](https://www.bits-pilani.ac.in/goa/snehanshus/profile), [Aditi Kathpalia](https://aditikathpalia.wordpress.com/), [Nithin Nagaraj](https://sites.google.com/site/nithinnagaraj2/)
-------------------------------------------------------------------------------------
#### Reference: Balakrishnan, Harikrishnan Nellippallil, et al. "[ChaosNet: A chaos based artificial neural network architecture for classification](https://aip.scitation.org/doi/abs/10.1063/1.5120831)". Chaos: An Interdisciplinary Journal of Nonlinear Science 29.11 (2019): 113125.
-------------------------------------------------------------------------------------
Inspired by chaotic firing of neurons in the brain, we propose ChaosNet—a novel chaos based artificial neural network architecture for
classification tasks. ChaosNet is built using layers of neurons, each of which is a 1D chaotic map known as the Generalized Luröth Series
(GLS) that has been shown in earlier works to possess very useful properties for compression, cryptography, and for computing XOR and
other logical operations. In this work, we design a novel learning algorithm on ChaosNet that exploits the topological transitivity property
of the chaotic GLS neurons. The proposed learning algorithm gives consistently good performance accuracy in a number of classification
tasks on well known publicly available datasets with very limited training samples. Even with as low as seven (or fewer) training samples/class
(which accounts for less than 0.05% of the total available data), ChaosNet yields performance accuracies in the range of 73.89% − 98.33%. 

-------------------------------------------------------------------------------------
## A Neurochaos Learning Architecture for Genome Classification
-------------------------------------------------------------------------------------
### Collaborators: [Nithin Nagaraj](https://sites.google.com/site/nithinnagaraj2/)
-------------------------------------------------------------------------------------
#### Reference: NB, Harikrishnan, Pranay SY, and Nithin Nagaraj. "[A Neurochaos Learning Architecture for Genome Classification](https://arxiv.org/abs/2010.10995)." arXiv preprint arXiv:2010.10995 (2020).
-------------------------------------------------------------------------------------
There has been empirical evidence of presence of non-linearity and chaos at the level of single neurons in biological neural networks. 
The properties of chaotic neurons inspires us to employ them in artificial learning systems. Here, we propose a Neurochaos Learning (NL) 
architecture, where the neurons used to extract features from data are 1D chaotic maps. ChaosFEX+SVM, an instance of this NL architecture,
is proposed as a hybrid combination of chaos and classical machine learning algorithm. We formally prove that a single layer of NL with a 
finite number of 1D chaotic neurons satisfies the Universal Approximation Theorem with an exact value for the number of chaotic neurons needed
to approximate a discrete real valued function with finite support. This is made possible due to the topological transitivity property of chaos
and the existence of uncountably infinite number of dense orbits for the chosen 1D chaotic map. The chaotic neurons in NL get activated under
the presence of an input stimulus (data) and output a chaotic firing trajectory. From such chaotic firing trajectories of individual neurons
of NL, we extract Firing Time, Firing Rate, Energy and Entropy that constitute ChaosFEX features. These ChaosFEX features are then fed to 
a Support Vector Machine with linear kernel for classification. The effectiveness of chaotic feature engineering performed by NL (ChaosFEX+SVM) 
is demonstrated for synthetic and real world datasets in the low and high training sample regimes. Specifically, we consider the problem of 
classification of genome sequences of SARS-CoV-2 from other coronaviruses (SARS-CoV-1, MERS-CoV and others). With just one training 
sample per class for 1000 random trials of training, we report an average macro F1-score > 0.99 for the classification of SARS-CoV-2 
from SARS-CoV-1 genome sequences. Robustness of ChaosFEX features to additive noise is also demonstrated.
