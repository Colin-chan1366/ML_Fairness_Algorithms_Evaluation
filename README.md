### GR5243 Spring 2024 Applied Data Science
### Project 4 Machine Learning Fairness Algorithms Evaluation

In this project, working in teams, you will implement, evaluate and **compare** algorithms for **Machine Learning Fairness**.

   - Algorithm 1: Fairness Constraints: Mechanisms for Fair Classification
   
   - Algorithm 2: Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment


### Team:
   - Jianfeng Chen (Colin)
   - Yiwei Jiang
   - Tianyi Chen
   - Yinpei Wang

### Challenge
*Machine Learning Fairness* refers to correcting the unfairness for certain groups or individuals in machine learning algorithms' predictions.

For this project, each team is assigned **specific algorithms** from the *Machine Learning Fairness* literature. You will study the algorithms carefully and implement them, from scratch. **Algorithm assignments will be posted to a piazza post**.

For submission, you will submit the GitHub repo of your codes, a *testing* report (must be a **reproducible** R/Python notebook) on the algorithms in terms of a *side-by-side* comparison of their performance and computational efficiency. 

You can use [Google Colab notebook](https://colab.research.google.com/#) if you're working in Python. It has the following advantages:

+ Zero configuration required
+ Free access to GPUs
+ Easy sharing 

It's not mandatoy for you to use Google Colab notebook if you're writing a Python notebook.

For presentation, each team should briefly explain 

+ what each algorithm does;
+ how the evaluation was carried out; 
+ and what are the main results. 

All developments need to be carried out in group-shared private repo on [https://www.github.com/TZstatsADS/] with clear project management log, taking advantage of GitHub issues. 

Each week, we will give a tutorial in class and having live discussion and brainstorm sessions. The instruction team will join team discussions during class and online. 

- week 1 : Introduction and project description.
- week 2 : Introduction to Machine Learning Fairness; Q&A.
- week 3 : Discussion of assigned algorithms.

#### Evaluation criteria 

- (7pts) Readabiity and reproducibility of codes
- (7pts) Validity of evaluation (well-defined measures of performance; experiment set up)
- (6pts) Presentation (report, github and in-class presentation)

*(More details will be posted as grading rubrics in courseoworks/canvas)*

# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

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

### Resources

#### Papers

1. [Information Theoretic Measures for Fairness-aware Feature selection](https://arxiv.org/abs/2106.00772)

2. [Learning Fair Representations](http://proceedings.mlr.press/v28/zemel13.html)

3. [Fairness Constraints: Mechanisms for Fair Classification](https://arxiv.org/abs/1507.05259)

4. [Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment](https://arxiv.org/abs/1610.08452)

5. [Fairness-aware Classifier with Prejudice Remover Regularizer](https://www.kamishima.net/archive/2012-p-ecmlpkdd-print.pdf)
   
6. [Handling Conditional Discrimination](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6137304)

#### Existing R/Python functions that can be part of your implementation. 

Unless otherwise instructed, you can use existing R/Python functions as part of your implementation. But, you'll be expected to write the main algorithm by yourself.
