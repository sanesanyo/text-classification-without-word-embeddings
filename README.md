# text-classification-without-word-embeddings
In this exercise, I have tried to test different algorithms to do supervsed text classifications. The data source used in this case is a 
public data set which has different research papers that featured in different conferences ("https://raw.githubusercontent.com/susanli2016/Machine-Learning-with-Python/master/research_paper.csv"). The aim of this task is to create a classification
model that can predict which conference the research paper is from.

I have started with a very simple naive bayes model and then after that tried the same bag of word representation on a SVM model (both linear and
non-linear). Followed by trying tfidf representation on the above models. Finally, I also try decision tree models such as random forest and
gradient boosted trees. The Naive Bayes showed the best performance out of all these models with SVM on tfidf presentation a close second.
I coul have also tried logistic regression but I did not expect a significantly better performance using it.

In the second repository (https://github.com/sanesanyo/text-classification-using-Fasttext-embeddings), I have continued this exercise by using
word embeddings as vector representation for my data and exploring if we see an improved performance.
