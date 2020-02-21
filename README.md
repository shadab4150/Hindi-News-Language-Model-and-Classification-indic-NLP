# Hindi News Language Model and Hindi News Classifier : indic NLP

* [**Notebook**](https://github.com/shadab4150/Hindi-News-Language-Model-and-Classification-indic-NLP/blob/master/Hindi_News_Language_Model_and_Classification_indic_NLP_v2.ipynb)

* In this project I trained Hindi Language Model with BBC Hindi News Dataset and then Built a Hindi News Classifier.

#### Dataset:

* [**BBC Hindi**](https://github.com/NirantK/hindi2vec/releases/tag/bbc-hindi-v0.1)

### Hindi Language Model:

* Architecture : **AWD-LSTM**  
* Learn more about **AWD-LSTM** Here **--->** [ASGD Weight-Dropped LSTM](https://medium.com/ai%C2%B3-theory-practice-business/awd-lstm-6b2744e809c5)

* **Model Summary :**

![kd](https://i.ibb.co/yqwzj9w/awd-lstm.jpg)

* **DataBlock :**

![kd](https://i.ibb.co/H4QcsvV/data-show.jpg)

* Used **Mixed Precision training** to decrease up the training time.

**Achieved a final accuracy of 30% for the Hindi Language Model**

![kd](https://i.ibb.co/QpqqbjG/lm.jpg)

### Completing sentences using Hindi Language Model

![kd](https://i.ibb.co/NKTyPnX/bbc-saudi.jpg)

![kd](https://i.ibb.co/tqP6yDZ/bbc-london.jpg)

## Hindi News Classifier

* **Hindi News Dataset :**

* Classifier Data Block

![kd](https://i.ibb.co/L68bX8P/hind-classifier.jpg)

* **News categories**
* **'business' , 'china' , 'entertainment' , 'india' , 'institutional' , 'international' , 'learningenglish'**
* **'multimedia' , 'news' , 'pakistan' , 'science' , 'social' , 'southasia' , 'sport'**

* Metrics I choose for the News dataset was a **f1_score**
> average = **macro**

* Because there was a class imbalance in the news dataset

#### Final f_beta score of the classifier was 0.789
![kd](https://i.ibb.co/hXGTsZg/class-final.jpg)

* **Top losses : **

![kd](https://i.ibb.co/kgWTP0N/top-losses.jpg)


## System Requirements

```
Python v3.6.x
fastai v1
Numpy
Pandas
tqdm (Progress bar)
Jupyter Notebook (Visualisations)

```

## Shoutout to

* Practical Deep Learning for Coders **MOOC** by team [**fast.ai**](https://www.fast.ai/)

