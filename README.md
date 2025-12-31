# Applications of Data and Machine Learning in Economic Research

These are slides from a **mini-course** that I taught as part of the undergraduate track *Mathematical and Computing Sciences for Artificial Intelligence* at Bocconi University in Fall 2025.

The goal is to illustrate how relatively simple algorithms, when combined with rich data,
can help answer important real-world policy questions. In particular, they explore how to predict **restaurant health violations** from customer reviews, improve the **placement of refugees** to improve integration, **detect poverty** from space, and apply deep neural networks to examine which facial features affect **judges' decisions** who to jail. 

The emphasis is on **ideas and intuition rather than technical detail**. The material is intended for students with a basic background in statistics, but no prior experience with machine learning or academic research.

## Lecture Overview

### Lecture 1 — Policymaking: Predicting Health Violations

Kang et al. (2013) study how public health agencies can target restaurant inspections more effectively when inspection resources are limited. They train a classification model that predicts health code violations using textual information from online restaurant reviews, alongside standard restaurant characteristics. The model shows that review text contains strong signals of hygiene problems and outperforms traditional indicators such as ratings or location. Targeting inspections based on these predictions could substantially increase the number of detected violations without increasing inspection capacity.

Kang et al. (2013), *Where Not to Eat? Improving Public Policy by Predicting Hygiene Inspections Using Online Reviews*  
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2293165

---

### Lecture 2 — Refugee Allocation: Algorithmic Assignment for Integration

Bansak et al. (2018) analyze how refugees are assigned to resettlement locations and show that employment outcomes vary strongly across locations and refugee characteristics. They train machine learning models to predict employment probabilities and combine these predictions with an optimization algorithm to reassign refugees subject to capacity constraints. The approach explicitly treats assignment as a matching problem rather than a prediction task alone. Simulations suggest that data-driven allocation could increase refugee employment by 40–70% without making any location worse off.

Bansak et al. (2018), *Improving Refugee Integration through Data-Driven Algorithmic Assignment*  
https://www.science.org/doi/10.1126/science.aao4408

---

### Lecture 3 — Poverty Measurement: Predicting Economic Well-Being from Space

Jean et al. (2016) address the lack of reliable poverty data in low-income countries by combining satellite imagery with machine learning. They train a convolutional neural network to predict night-time light intensity from daytime images and use the learned features to estimate local consumption and wealth. This transfer-learning approach allows the model to extract economically meaningful surface features such as infrastructure and settlement patterns. The resulting predictions explain a large share of variation in poverty and generalize across countries.

Jean et al. (2016), *Combining Satellite Imagery and Machine Learning to Predict Poverty*  
https://www.science.org/doi/10.1126/science.aaf7894

---

### Lecture 4 — Judicial Decisions: Machine Learning for Hypothesis Generation

Ludwig and Mullainathan (2024) study judicial pre-trial detention decisions and show how machine learning can be used to generate new scientific hypotheses. They train a model that predicts judges’ decisions using case characteristics and defendants’ facial images, and then use generative techniques to systematically modify faces while holding them realistic. By combining model output with human interpretation, the authors identify previously unstudied facial features that influence detention decisions. The paper demonstrates how machine learning can complement traditional econometrics by guiding hypothesis formation.

Ludwig and Mullainathan (2024), *Machine Learning as a Tool for Hypothesis Generation*  
https://academic.oup.com/qje/article/139/2/751/7470044


## License

Unless otherwise noted, all original content in this repository
(text and layout) is licensed under the  
**Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Third-party materials (figures, images, or excerpts) are included
for educational purposes and are **not** covered by this license.
Such materials remain
the property of their original copyright holders.

## Attribution

If you reuse or adapt this material, please credit:

Julian Streyczek  
https://github.com/JulianStreyczek/Machine-Learning-in-Economic-Research
