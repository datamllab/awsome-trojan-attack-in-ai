# Awesome-Fairness-in-AI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but probably biased and incomplete, list of awesome Fairness in AI resources.

If you want to contribute to this list, feel free to pull a request. Also you can contact [Mengnan Du](http://people.tamu.edu/~dumengnan/) from the [Data Lab](http://faculty.cs.tamu.edu/xiahu/) at Texas A&M University through email: dumengnan@tamu.edu, or Twitter [@DuMNCH](https://twitter.com/DuMNCH).


## What is Fairness in AI?

AI algorithms are increasingly being used in high-stake decision making applications that affect individual lives. However, AI might exhibit algorithmic discrimination behaviors with respect to protected groups, potentially posing negative impacts on individuals and society.

Fairness in AI (FAI) aims to build fair and unbiased AI/machine learning systems, that ensure the benefits are broadly available across all segments of society. Specific topics include but are not limited to: theoretical understanding of algorithmic bias, defining measurements of fairness, detection of adverse biases, and developing mitigation strategies.


## Table of Contents

* [Review and General Papers](#review-and-general-papers)
* [Measurements of Fairness](#measurements-of-fairness)
* Fairness of Machine Learning Models
  * [Prediction Outcome Discrimination](#prediction-outcome-discrimination)
  * [Predictive Accuracy Disparity](#predictive-accuracy-disparity)
* [Fairness of Representations](#fairness-of-representations)
* [Fairness Packages and Frameworks](#fairness-packages-and-frameworks)
* [Conferences](#conferences)
* [Other Fairness Relevant Interpretability Resources](#other-fairness-relevant-interpretability-resources)
  

## Review and General Papers

* [Fairness in Deep Learning: A Computational Perspective](https://arxiv.org/pdf/1908.08843.pdf)
* [The Measure and Mismeasure of Fairness: A Critical Review of Fair Machine Learning](https://arxiv.org/pdf/1808.00023.pdf)
* [Fairness and machine learning](https://fairmlbook.org/)
* [A Survey on Bias and Fairness in Machine Learning](https://arxiv.org/pdf/1908.09635.pdf)
* [The Frontiers of Fairness in Machine Learning](https://arxiv.org/pdf/1810.08810.pdf)
* [Ensuring fairness in machine learning to advance health equity](https://annals.org/aim/fullarticle/2717119)
* [Mitigating Gender Bias in Natural Language Processing: Literature Review](https://www.aclweb.org/anthology/P19-1159.pdf)
* [Fairness in Recommender Systems](http://www.ec.tuwien.ac.at/~dimitris/research/recsys-fairness.html)



## Measurements of Fairness

* [On Formalizing Fairness in Prediction with Machine Learning](https://arxiv.org/pdf/1710.03184.pdf)
* [Equality of Opportunity in Supervised Learning](https://arxiv.org/pdf/1610.02413.pdf)
* [Certifying and removing disparate impact](https://arxiv.org/pdf/1412.3756.pdf)
* [Does mitigating ML's impact disparity require treatment disparity?](https://papers.nips.cc/paper/8035-does-mitigating-mls-impact-disparity-require-treatment-disparity.pdf)
* [Putting Fairness Principles into Practice: Challenges, Metrics, and Improvements](https://arxiv.org/pdf/1901.04562.pdf)
* [Beyond Parity: Fairness Objectives for Collaborative Filtering](https://arxiv.org/pdf/1705.08804.pdf)
* [50 Years of Test (Un)fairness: Lessons for Machine Learning](https://arxiv.org/pdf/1811.10104.pdf)


## Fairness of Machine Learning Models

### Prediction Outcome Discrimination

* Bias Amplification Phenomenon
  * [Women Also Snowboard: Overcoming Bias in Captioning Models](http://openaccess.thecvf.com/content_ECCV_2018/papers/Lisa_Anne_Hendricks_Women_also_Snowboard_ECCV_2018_paper.pdf)
  * [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://arxiv.org/pdf/1707.09457.pdf)
  * [Feature-Wise Bias Amplification](https://arxiv.org/pdf/1812.08999.pdf)
  * [ConvNets and ImageNet Beyond Accuracy: Understanding Mistakes and Uncovering Biases](https://arxiv.org/pdf/1711.11443.pdf)


* Adversarial Learning to Mitigate Discrimination
  * [Data Decisions and Theoretical Implications when Adversarially Learning Fair Representations](https://arxiv.org/pdf/1707.00075.pdf)
  * [Achieving Fairness through Adversarial Learning: an Application to Recidivism Prediction](https://arxiv.org/pdf/1807.00199.pdf)
  * [Balanced Datasets Are Not Enough: Estimating and Mitigating Gender Bias in Deep Image Representations](https://arxiv.org/pdf/1811.08489.pdf)
  * [Mitigating Unwanted Biases with Adversarial Learning](https://arxiv.org/pdf/1801.07593.pdf)
  * [Adversarial Removal of Demographic Attributes from Text Data](https://arxiv.org/pdf/1808.06640.pdf)

* Other Detection and Mitigation Papers
  * [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://arxiv.org/pdf/1805.04508.pdf)
  * [Reducing Gender Bias in Abusive Language Detection](https://arxiv.org/pdf/1808.07231.pdf)
  * [Turning a Blind Eye: Explicit Removal of Biases and Variation from Deep Neural Network Embeddings](https://arxiv.org/pdf/1809.02169.pdf)
  * [REPAIR: Removing Representation Bias by Dataset Resampling](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_REPAIR_Removing_Representation_Bias_by_Dataset_Resampling_CVPR_2019_paper.pdf)
  


### Predictive Accuracy Disparity

* [Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf)
* [Deep Learning for Face Recognition: Pride or Prejudiced?](https://arxiv.org/pdf/1904.01219.pdf)
* [Why Is My Classifier Discriminatory?](https://papers.nips.cc/paper/7613-why-is-my-classifier-discriminatory.pdf)
* [InclusiveFaceNet: Improving Face Attribute Detection with Race and Gender Diversity
](https://arxiv.org/pdf/1712.00193.pdf)
* [Demographic Dialectal Variation in Social Media: A Case Study of African-American English](https://aclweb.org/anthology/D16-1120/)
* [Incorporating Dialectal Variability for Socially Equitable Language Identification](https://www.aclweb.org/anthology/P17-2009/)
* [Decoupled Classifiers for Group-Fair and Efficient Machine Learning](http://proceedings.mlr.press/v81/dwork18a.html)
* [Mitigating Bias in Gender, Age and Ethnicity Classification: a Multi-Task Convolution Neural Network Approach](https://hal.inria.fr/hal-01892103/document)



## Fairness of Representations

* [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://arxiv.org/pdf/1607.06520.pdf)
* [Learning Gender-Neutral Word Embeddings](https://arxiv.org/pdf/1809.01496.pdf)
* [Flexibly Fair Representation Learning by Disentanglement](https://arxiv.org/pdf/1906.02589.pdf)
* [Gender Bias in Contextualized Word Embeddings](https://arxiv.org/pdf/1904.03310.pdf)



## Fairness Packages and Frameworks

* [AI Fairness 360](https://github.com/IBM/AIF360)
* [fairlearn: Fairness in machine learning mitigation algorithms](https://github.com/fairlearn/fairlearn)
* [algofairness](https://github.com/algofairness)
  * [fairness: Benchmarking of fairness aware machine learning algorithms](https://github.com/algofairness/fairness-comparison)
* [FairSight: Visual Analytics for Fairness in Decision Making](https://arxiv.org/pdf/1908.00176.pdf)



## Conferences

* [FAT\*: ACM Conference on Fairness, Accountability, and Transparency](https://fatconference.org/)
* [FATML: Fairness, Accountability, and Transparency in Machine Learning Workshop](https://www.fatml.org/)
* [AIES: AAAI/ACM Conference on AI, Ethics, and Society](http://www.aies-conference.com/2020/)


## Other Fairness Relevant Interpretability Resources

* [Awesome machine learning interpretability resources](https://github.com/jphall663/awesome-machine-learning-interpretability)
* [The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490.pdf)
* [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/pdf/1702.08608.pdf)
* [Techniques for Interpretable Machine Learning](https://arxiv.org/pdf/1808.00033.pdf)
* [Methods for Interpreting and Understanding Deep Neural Networks](https://arxiv.org/pdf/1706.07979.pdf)





