---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about
  - /about.html
---

I am currently a second-year Ph.D. student at the University of Texas at Dallas. Before this, I worked as a Data Scientist at Mercedes Benz Research and Development, India, from January 2018 - November 2020.

My research centers on developing techniques and algorithms that enable data-efficient, compute-efficient, and robust machine learning systems. I am interested in designing techniques that use the underlying data structure and analyze data samples' importance for model learning to achieve the earlier goals. My current work on data subset selection focuses on selecting small data subsets on which the machine learning models can be trained with negligible loss in accuracy on unseen datasets(generalization) while achieving 5X - 10X speedups/ energy savings/ CO2 emission savings. Another critical aspect of the data subset selection methods is that we can efficiently use them for training the models robustly when the dataset has noisy labels and class imbalance. I am also interested in designing techniques for label-efficient machine learning through the lens of active learning, semi-supervised learning, data programming, and labeling functions paradigms. My research directly applies to building machine learning systems that can efficiently learn from a prohibitively massive amount of data in a scalable and robust manner and brings us one step closer to achieving Green AI {% cite Schwartz2020GreenA %}.

For more details on my research, please check my [research](/research) page. For details on my publications, please check my [publications](/publications) page.


References
----------
{% bibliography --cited %}