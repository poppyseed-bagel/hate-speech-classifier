#  Classifying Toxic Comments Online

## Grade: 99/100

### Assignment write-up alongside code is found in `writeup/writeup.pdf`
### For access to code-only version, go to `code/classifier.rmd`

Group project for Applied Machine Learning. This classifier looks at a dataset of 100,000+ Wikipedia comments which have been pre-labeled as hate speech or not to create an algorithim to identify hate speech in unseen comments. The project required data cleaning, feature selection, and model tuning. The project used 4 different algorithims: LASSO, Random Forest, Support Vector Machines (SVM), and Naive Bayes. We found that the SVM model performed the best, with a CV error of .74 and a test error of .71. 

*Content warning: This competition makes use of data from a project to automate moderation of toxic speech online. Many comments in this dataset contain hate speech and upsetting content.*

This problem set involves classification of toxic comments in Wikipedia talk pages.

Your task is to use what you have learned in class to build a classifier that performs well on a test set with the true labels obfuscated to prevent cheating. All of the comments were hand-labeled by multiple coders for the paper ["Ex Machina: Personal Attacks Seen at Scale"](https://arxiv.org/abs/1610.08914).
