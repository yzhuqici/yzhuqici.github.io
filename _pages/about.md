---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>



I am currently a Research Assistant Professor at the Quantum Information and Computation Initiative at the University of Hong Kong. I obtained a PhD in Computer Science from the University of Hong Kong (2024; supervisor: [Giulio Chiribella](https://scholar.google.com/citations?user=4ob0VU4AAAAJ&hl=en&oi=ao)) and a Bachelor in Computer Science from Zhejiang University (2019).

I have published papers in top journals including Nature Communications, Physical Review Letters, and npj Quantum Information. My research interests include AI for Science and Quantum Machine Learning, with a recent focus on representation learning of quantum systems.

# 📝 Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Communications 13 (1), 1-10</div><img src='images/state_learning.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Flexible learning of quantum states with generative query neural networks](https://www.nature.com/articles/s41467-022-33928-z)

Yan Zhu*, Ya-Dong Wu\*$^\dagger$, Ge Bai, Dong-Sheng Wang, Yuexuan Wang, Giulio Chiribella$^\dagger$

- In this paper, we introduce a network that can be trained with data from a fiducial set of states and measurements, and can later be used to characterize quantum states that share structural similarities with the fiducial states. With little guidance of quantum physics, the network builds its own data-driven representation of a quantum state, and then uses it to predict the outcome statistics of quantum measurements that have not been performed yet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Physical Review Letters 130 (21), 210601</div><img src='images/state_verification.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quantum Similarity Testing with Convolutional Neural Networks](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.130.210601)

Ya-Dong Wu\*, Yan Zhu\*$^\dagger$, Ge Bai, Yuexuan Wang, Giulio Chiribella$^\dagger$

- In this Letter, we develop a machine learning algorithm for comparing unknown continuous variable states using limited and noisy data. Our network can even be applied to the problem of comparing continuous variable states across different experimental platforms, with different sets of achievable measurements, and to the problem of experimentally testing whether two states are equivalent up to Gaussian unitary transformations.

​		</div>
​		</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv:2308.08815</div><img src='images/process_learning.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predictive Modelling of Quantum Process with Neural Networks](https://arxiv.org/abs/2308.08815)

Yan Zhu\*, Ya-Dong Wu\*$^\dagger$, Qiushi Liu, Yuexuan Wang, Giulio Chiribella$^\dagger$

- In this paper, we introduce a neural network that emulates the unknown process by constructing an internal representation of the input ensemble and by mimicking the action of the process at the state representation level. We show that our model exhibits high accuracy in applications to quantum computing, quantum photonics, and quantum many-body physics.

  </div>
  </div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv: 2310.11807</div><img src='images/property_learning.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning quantum properties from short-range correlations using multi-task networks](https://arxiv.org/abs/2308.08815)

Ya-Dong Wu\*, Yan Zhu\*$^\dagger$, Yuexuan Wang, Giulio Chiribella$^\dagger$

- In this paper, we develop a multi-task neural network model that can accurately predict global properties of many-body quantum systems, like string order parameters and many-body topological invariants, using only limited measurement data gathered from few neighbouring sites. Remarkably, our model appears to be able to transfer information learnt from lower dimensional quantum systems to higher dimensional ones, and to make accurate predictions for Hamiltonians that were not seen in the training.

​		</div>
​		</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> arXiv:2311.01727</div><img src='images/error_mitigation.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Flexible Error Mitigation of Quantum Processes with Data Augmentation Empowered Neural Model](https://arxiv.org/abs/2311.01727)

Manwen Liao\*, Yan Zhu\*, Giulio Chiribella, Yuxiang Yang$^\dagger$

- In this paper, we propose a data augmentation empowered neural model for error mitigation (DAEM). Our model does not require any prior knowledge about the specific noise type and measurement settings and can estimate noise-free statistics solely from the noisy measurement results of the target quantum process, rendering it highly suitable for practical implementation.

# 🎖 Awards

- *2023.2* HKU Foundation Publication Award for Research Postgraduate Students

  

# 💬 Contributed Talks

- *2022.11*, 6th Quantum Techniques in Machine Learning (QTML), Naples, Italy.
- *2023.8*, 23rd Asian Quantum Information Science Conference (AQIS), KIAS, Korea.
- *2023.11*, 7th Quantum Techniques in Machine Learning (QTML), CERN, Switzerland.
- *2024.07*, Quantum Errors, Sensing and Control: Principles, Applications and Engineering (Q-ESCAPE), Shenzhen, China.

