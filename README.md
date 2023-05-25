# CS273A_Machine_Learning
CS273A ML final projects
The purpose of this project is to develop classification models that can accurately predict whether the
income of an individual is over 50K per year by exploring and analyzing the Adult dataset. In this
project, we will conduct various visualization to explore the data. Moreover, we will perform data
preprocessing, feature selection, model training and selection to figure out the appropriate classification
model which has the best performance in predicting income based on the available data.

**Below is the Adult Data Set url:**
https://archive.ics.uci.edu/ml/datasets/Adult

**https://github.com/kireikirei/CS273A_Machine_Learning/blob/main/README.md#:~:text=CS273a_Project_random_forest is the code with implementation of data visulization, preprocessing, feature selection, training of random forest and model evaluation.**

## Project Requirements:

Explore the various aspects of the data, visualizing and analyzing it in different ways. It is really important that you are familiar with it. You should describe how you made various design choices, based on the dataset exploration.

1. Exploration of at least one or two techniques on which we did not spend significant time in class. For example, using neural networks, support vector machines, or random forests are great ideas; but if you do this, you should explore in some depth the various options available to you for parameterize the model, controlling complexity, etc. (This should involve more than simply varying a parameter and showing a plot of results.)

2. Other options might include feature design, or optimizing your models to deal with special aspects of the data (missing features, too many features, large numbers of zeros in the data; possible outlier data; etc.). Your report should describe what aspects you chose to focus on.

3. Performance validation. You should practice good form and use validation or cross-validation to assess your models’ performance, do model selection, combine models, etc. You should not simply try a few variations and assume you are done.

4. Adaptation to under- and over-fitting. Machine learning is not very “one size fits all”; it is impossible to know for sure what model to choose, what features to give it, or how to set the parameters until you see how it does on the data. Therefore, much of machine learning revolves around assessing performance (e.g., is my poor performance due to underfitting, or overfitting?) and deciding how to modify your techniques in response. Your report should describe how, during your process, you decided how to adapt your models and why.

### Some possible components recommended by professor:

Semi-supervised methods: investigate how your knowledge of the test features can be used to improve prediction. As examples, see e.g., label propagation (http://www.cs.cmu.edu/~zhuxj/pub/CMU-CALD-02-107.pdfLinks to an external site.), or using EM (within e.g. naive Bayes or a Gaussian mixture model, e.g., http://www.kamalnigam.com/papers/emcat-mlj99.pdfLinks to an external site.).

Kernel learning, or similarity/metric learning of the measure of dissimilarity used in, for example, nearest neighbors or SVMs, to improve their performance. See for example Weinberger and Saul 2008, http://www.cse.wustl.edu/~kilian/papers/jmlr08_lmnn.pdfLinks to an external site..

Neural networks and deep learning; using existing packages like PyTorch, Keras, MxNet, and PyLearn2.

Support vector machines. For example, you could investigate the effect of different kernel choices, regularization, etc.). The implementation libsvm is pretty good.

Go in-depth with ensembles. Use lots of learners, stacking, and information from your leaderboard performance to try to improve your prediction quality.

Feature selection methods, such as stepwise regression (or in this case, classification); e.g. http://en.wikipedia.org/wiki/Stepwise_regressionLinks to an external site.. (Note: if you use feature selection, you should use a predictor that is sufficiently complex to need feature selection!)

New Features Techniques for creating new features, including “kitchen sink” features (http://books.nips.cc/papers/files/nips21/NIPS2008_0885.pdfLinks to an external site.), clustering-based features, etc. Once you have many features, of course, you may also have to explore feature selection (see above) or regularization to control complexity.

Sophisticated decision tree structures, e.g., http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.54.1587Links to an external site..

etc.
