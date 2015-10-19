Empirical studies supporting gamification in software engineering, tools used and frameworks that assist in building gamified tools have been published. Most of these studies deal either with usability of the tool determined by surveys or the involvement of users as a metric to evaluate the usefulness of gamification. Both these methods involves humans.  But there is no study which involves metrics to qualitatively evaluate the usefulness of gamification on Software engineering practices. We train a model and apply this model to predict the usefulness of code review comments given by using the gamified tools.

To perform this study, we employed five tools(2 non-gamified and 3 gamified) to gather the code review comments in both the categories. supporting arguments on choice of tools we selected is described further in the paper.

Out of the five tools we adopted, one tool is built using an extensible framework which we have developed to suite the needs of software engineering and comprise of the game design elements\cite{what are game design elements paper} suitable for software engineering\cite{GDE suitable for SE paper}.

The possibility of extraction of code review data has a huge impact in selection of the tools we employed. For the empirical study to be feasible, complete code review data involving code review comments, changeset details, date and time of comments, developer details and reviewer details are essential. We extracted these details from the toosl and exported them in csv format.

The data we extracted is to be cleaned and converted into features to be fed to a model which will predict the usefulness of comments. For this, we pre-processed the data by following the standard procedure to clean data(involving removing white-space, punctuation, and numbers, converting
all words to lower case) followed by removing common english stop-words. Then we apply stemming\cite{porter stemming} to reduce the inflected words to their word stem. Word stem is a word without suffixes/prefixes/derivational morphemes (e.g. the derived verbs black-en or standard-ize) etcerta..

This pre-processed data is then served to feature extraction algorithms. As a well known fact, there is no free lunch in finding a better feature extraction algorithm, hence we analysed our study using  TF-IDF, NGram and word2vec algorithms. Our results suggest that word2vec indicates similarity between words for natural language involved in code reviews will generate features when applied on modelling algorithms like SVM/KNN/NB produces better predictions. (Results to show the best combination between TF-IDF|NGRAM|Word2vec and NB|SVM|KNN.

The model we built to predict usefulness has been fed with training data from : earlier microsoft study\cite{p146-bosu paper}, stackexchange's code review data and the code review comments which we manually classified into usefull and notusefulfull based on 1,2,3,4,5 attributes. (as of now,we classifying manually is optional).

The results can also talk on why Kernel ridge regression or Stochastic Gradient Descent or any classification algorithm (even svm|NB|KNN) may not produce better prediction for SE data.

We imply the model we built to predict usefulness on code review data that is collected on gamified applications and non-gamified applications and visualize the usefullness of gamification quantitatively as well as qualitatively.

