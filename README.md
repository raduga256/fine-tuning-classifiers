# fine-tuning-classifiers
A Collection of Model Fine Tuning Research Projects

It’s easy to understand that many machine learning problems benefit from either precision or recall as their optimal performance metric but implementing the concept requires knowledge of a detailed process. My first few attempts to fine-tune models for recall (sensitivity) were difficult, so I decided to consolidate and grow my experience by using a Kevin Arvai tutorial on the medium website.
My aim was not to build a robust classifier, rather I wanted to show the practicality of optimizing a classifier for sensitivity. In figure A below, the goal is to move the decision threshold to the left. This minimizes false negatives, which are especially troublesome in the dataset chosen for this post. It contains features from images of 357 benign and 212 malignant breast biopsies. A false negative sample equates to missing a diagnosis of a malignant tumor. The data file can be downloaded here.
![image](https://user-images.githubusercontent.com/56635875/117510699-72b5e800-af84-11eb-8cf5-d1888d6a291a.png)
![image](https://user-images.githubusercontent.com/56635875/117510653-5d40be00-af84-11eb-9afd-7b3e5c9c5cf1.png)

