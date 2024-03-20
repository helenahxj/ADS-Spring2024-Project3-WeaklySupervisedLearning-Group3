# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2024

+ Team 3
+ Team members
	+ Yerin Cho
	+ Aojie Li
	+ Siyu Li
	+ Xiangjing Hu

+ Project summary: In this project, we addressed the challenge of image classification with noisy labels by developing 3 models. The baseline model utilized logistic regression with RGB histogram features. Our first advanced model (Model I) was a Convolutional Neural Network (CNN) trained directly on noisy labels. We further evolved our approach by introducing Model II, which incorporated weakly supervised learning with a novel loss function and high-confidence prediction to improve robustness against label noise. This model significantly outperformed the baseline and Model I, demonstrating the efficacy of our methods in enhancing classification accuracy in the presence of noisy data. 
	
**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. Yerin is responsible for creating the first CNN model and train the first model. Siyu split dataset to train the first model and further optimized our two models for better performance. Aojie is responsible for improve the accuracy for our model, by adding weakly supervised learning features to the CNN model and use iterative method to the training set. Xiangjing split dataset and adjust relevant features and parameters to further improve accuracy for the second model and plot accuracy and loss over epoch for training and validation data for each model. Xiangjing is also responsible for the evaluating models performance and output enhanced models and the label predicted by all three models.

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
