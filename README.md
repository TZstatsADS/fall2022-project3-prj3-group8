# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2022

+ Team 8
+ Team members
	+ Zhejing Shi
	+ Jiapeng Xu
	+ Yudan Zhang
	+ John Podias

+ Project summary: In this project, we built two image classification models that build upon the baseline logistic regression model that has very low accuracy. Our model 1 uses neural network methods and still has low accuracy of 20 percent due to the label noise. Our model 2 uses a similar model, but does label correction to improve accuracy. This final model gives us a 70 percent accuracy.
	
**Contribution statement**: in this project, Zhejing Shi & Jiapeng Xu mostly focus on coding model I & II. Yudan Zhang & John Podias are mainly 
responsible for organizing output & editing documents for presenting.

All team members contributed to the planning sessions  and researching for ideas on weakly supervized learning.
1. Jiapeng Xu helped build model 1 and researched on transfer learning and image augmentation. He tried his own method training model 2 and got the accuracy of 50%. 
2. Zhejing Shi helped develop model 1 and model2 and debug the models. For model 2 he applied the label updating and selection technique to make predictions, and his final model gave us a 70% accuracy. He also researched and applied techniques such as early stopping and transfer learning. Helped organize github files.
3. Yudan Zhang researched Label Cleaning technique, make model architecture drawings for Powerpoint, orgnize Github files, and prepared the presentation documentation
4. John Podias helped with presentation documentation, orgnize Github files, and present our work to the class


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
	└── main.ipby
	└──main.pdf
	└──Model_clean.h5
	└──Model_final.h5

├── figs/
└── output/
```

Please see each subfolder for a README file.
