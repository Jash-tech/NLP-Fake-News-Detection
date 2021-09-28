# NLP-Fake-News-Detection
Fake News is often done to further certain ideas or political agendas. Such news items may contain false or exaggerated claims, and may end up being viralized by algorithms.
This python project of detecting fake news deals with fake and real news. Using sklearn, we build a TfidfVectorizer on our dataset. Then, we initialize a PassiveAggressive Classifier and fit the model. In the end, the accuracy score and the confusion matrix tell us how well our model fares.<br>

We took a [political dataset](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view), implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier, and fit our model.
So with this model, we have 570 true positives, 611 true negatives, 45 false positives, and 41 false negatives.We ended up obtaining an accuracy of 93% in magnitude.

Credits: Dataset has bee taken from Data Flair.Thanks for the steps and guidance for this beginner NLP model.
