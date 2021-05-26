# Text_classification_to_topics
It consists of machine learning model developed to classify the text to the topic it belongs. I have primarily used **Naive Bayes** classifier.  

for detailed report click [Report of text classification problem](

## 📄 Description

The dataset consist of two columns, one is 'Text' where the text data is given and another is 'Target' where corresponding class of topic for the text data is given. we have to classify the text to its true class of topic.

I have used **Naive Bayes classifier** with oversampling and also built a model for same data using **SVM**. Beofore that, performed general techniques of data-preprocessing like stemming, vectorization which are needed for any natural language processing problem. Also used SVM to build the model using same dataset, done oversamling as class imbalance effects the predictions.

### Evaluated the model with accuracy, F1 score and confusion matrix
#### For Naive Bayes
|                   | accuracy( on test data) | F1 score      |
| ----------------- | ----------------------- | ------------- |
| without sampling  |         0.546           |     0.3369    |
| with sampling     |         0.5914          |     0.5938    |

### Limtations of Naive Bayes

- Naive Bayes classifier is bad at classification if any new word comes in the instance as the probabilty for any class is calculated zero here.
- Naïve Bayes assumes every feature (word in text) independent of other. But this is rarely true in the real world.

### Addition points
In addition, I have trained SVM for same problem and compared it with Naive Bayes.

## 💾 Datasset

- The dataset is taken from ROOT2AI Technology Pv. Ltd. 
https://docs.google.com/spreadsheets/d/1DLL6BTXiHHsn1w9NvVi0BZbass0QU0RSvKEXtJlwfCM/


## 🛠️ Requirements

- Python 3+
- IDE for python
- nltk library
- sklearn library
- imblearn library

