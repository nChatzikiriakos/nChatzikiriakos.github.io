---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

To use data-driven methods for safety critical applications, especially in control, it is important to account for the uncertainty in the data, which is due to, often probabilistic, noise.
Hence, in my research my goal is to leverage tools from statistical learning theory, machine learning and control theory in order to understand the fundamental hardness of learning and to provide means for provably safe data-driven application in these scenarios. 
### Finite Sample Identification of Dynamical Systems 
Recent advances in statistical learning theory have provided the means to analyze system identification from a non-asymptotic perspective, i.e., when the number of samples is finite. 
This finite sample analysis has sparked novel results for the statistical hardness of learning linear and certain classes of non-linear systems from i.i.d. as well as trajectory data. While these results already tell us much, there are still some shortcomings compared to the asymptotic analysis as well as potentially restrictive assumptions which I seek to reduce trough my research.
### Active Learning of Dynamical Systems
The predominant part of the finite sample system identification literature considers the case where the input is chosen i.i.d. (sub-)Gaussian. From a dynamical systems and control engineering perspective it is known that this is often not the optimal choice in terms of the sample complexity. 
Thus, I seek to identify suitable control inputs for a more sample efficient data collection and aim to develop tools to analyze these active learning scenarios.
### Uncertainty Quantification for data-driven control
A key challenge in providing data-driven control schemes with end-to-end guarantees lies in handling the uncertainty carried by the data. 
While there exist indirect data-driven control schemes for LTI systems that are equipped with end-to-end guarantees there is still an open gap, especially when it come to considering the interplay between finite sample identification error bounds and a controller that is robust with respect to this error. 
