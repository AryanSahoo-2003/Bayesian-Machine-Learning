# Bayesian Machine Learning
## Introduction

This repository contains my implementations for various machine learning and data science tasks. The tasks I have implemented in this repository include Task 1, Task 2, Task 3, Task 5, and Task 7. I have also uploaded the Jupyter .ipynb files for each task.

### Task 1: Fréchet Distribution

In this task, I have implemented Inverse CDF sampling for the Fréchet distribution. I generated a sufficient number of samples and plotted the kernel density estimation plot. I was able to match the PDF of the Fréchet distribution. Furthermore, I reproduced the following figure to visualize the distribution: https://en.wikipedia.org/wiki/File:Frechet_pdf.svg

### Task 2: Information Theory

For this task, I have briefly explained and implemented five functions :

 -   Cross-entropy
 -   Entropy
 -   Mutual information
 -   Conditional entropy
 -   KL divergence

I have taken appropriate example toy data/distributions and explained the insights from calculating these quantities.
### Task 3: Air Quality Prediction

I downloaded a week of PM2.5 dataset from the OpenAQ website for Delhi for this task. After filling in the missing data with appropriate methods, I used three regressors: i) the sklearn Random Forest regressor; ii) sklearn Linear regression; and iii) Gaussian process regressor to interpolate the PM2.5 values across the space. I used all the available features that I could get from the OpenAQ website or elsewhere (e.g., meteorological variables). Finally, I compared the results and prepared a table showing the metrics in K-Fold cross-validation setting.
### Task 5: Neural Architecture Search

In this task, I have summarized the paper "Deep Reinforcement Learning with Feedback-based Exploration" within 200 words. The paper proposes a new deep reinforcement learning method that uses feedback-based exploration to learn more efficiently and achieve better performance on tasks than existing reinforcement learning methods.
### Task 7: Bayesian Inference

n this task, I had a box of coins where any randomly chosen coin follows a Kumaraswamy distribution with a=2, b=3. I picked a coin at random and tossed it ten times, which yielded = [H, T, H, H, T, H, H, H, H, H]. Using Bayes rule, I found the probability distribution of the coin that was picked up. If the posterior was available in closed-form, I visualized the resultant distribution. Otherwise, I showed the calculations up to the step where it became intractable to solve further. Finally, I used the blackjax library with NUTS sampler to find the posterior distribution and plotted it.

### Files

This repository contains the following files:

  ->  Task1.ipynb: Contains the code and explanation for Task 1
  ->  Task2.ipynb: Contains the code and explanation for Task 2
  ->  Task3.ipynb: Contains the code and explanation for Task 3
  ->  Task5.ipynb: Contains the code and explanation for Task 5
  ->  Task7.ipynb: Contains the code and explanation for Task 7

### Requirements

The following packages are required to run the code:

   -> numpy
   -> pandas
   -> matplotlib
   -> seaborn
   -> scikit-learn
    
### Usage

  1.  Clone the repository to your local machine.
  2.  Install the required packages using pip.
  3.  Open the Jupyter Notebook (.ipynb) file for the task you want to run.
  4.  Run the code cell by cell.

### Conclusion

This repository contains my implementations for various machine learning and data science tasks. I have also uploaded the Jupyter .ipynb files for each task.
