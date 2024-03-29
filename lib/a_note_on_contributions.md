### A Note on Contributions

Whenever we have team projects, there are always concerns on unequal contributions from members of a project team. In the ideal world, we are all here to put in our best efforts and learn together. Even in that ideal world, we have different skill sets and preparations, and we will still contribute differently to a project. 

Therefore, you are required to post a *contribution statement* in the root README.md of your GitHub repo. Please beware that your GitHub repo will become public and remain public after the due date of the projects. 

Post your title, team members, project abstract and a contribution statement in the README.md file.  This is a common practice for research scientific journals. 

Below is an example. If no contribution statement is provided, we will insert a default statement that goes "**All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement**. "

---
Sample project README statement.

Project 4

Team members: Jianfeng Chen(Colin), Sally Zhao, Shoufei Meng, Chulin Tang, Peng Jiang

Summary: 

In this project, implements a CNN model with a Label Correction Network for image classification. It utilizes both clean and noisy labeled data for training. The CNN extracts image features, while the Label Correction Network learns to "clean" the noisy labels using the image features and original noisy labels. The model is trained on the noisy data, with the Label Correction Network regularizing the training process. Validation is performed on a separate dataset containing both clean and noisy labels, and the best model is saved based on validation accuracy. This semi-supervised approach leverages limited clean data and abundant noisy data for improved performance.

[Contribution Statement] 

Colin designed the study which include 'Learning From Noisy Large-Scale Datasets With Minimal Supervision' and 'Multi-Label Fashion Image Classification with Minimal Human Supervision', exploring feature engineering for improving the baseline model and implement a ResNet as well as Label Clean Network to achieve 50% accuracy finally. Sally also designed the study using the second method described in 'Multi-Label Fashion Image Classification with Minimal Human Supervision'. She developed the CNN classification model as well as label Clean Network for 61% accuracy achievement (both model 1 and model 2). AB, EF and GH discussed and designed the model evaluation protocol. She also carried out the computation for model evaluation and created graphs and visualizations. Sally conducted the in-class test data performance analysis. Shoufei Meng contributed to the GitHub repository and prepared the presentation. All team members approve our work presented in our GitHub repository including this contribution statement.
