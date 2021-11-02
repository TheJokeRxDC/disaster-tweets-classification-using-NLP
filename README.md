# Disaster Tweets Classification Using Natural Language Processing (NLP)
![image](https://user-images.githubusercontent.com/23554465/139895715-45bf4b3a-f381-4820-b72c-5990812024fc.png)

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster.

This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here.

Tweet source: https://twitter.com/AnyOtherAnnaK/status/629195955506708480

Competition link : https://www.kaggle.com/c/nlp-getting-started/overview

Dataset : https://www.kaggle.com/c/nlp-getting-started/data

## Table of Contents

1. Environment Setup
2. Dataset Loading
3. Exploratory Data Analysis (EDA)
4. Text Preprocessing
5. Bag-of-Words (BoW)
6. TF-IDF
7. Machine Learning Model Experimentation <br>
  7.1 Bag-of-Words (BoW) Experimentation <br>
  7.2 TF-IDF Experimentation <br>
8. Deep Learning Model Experimentation <br>
  8.1 Model 1 : Feed-Forward Network + Embedding Layer <br>
  8.2 Model 2 : Recurrent Neural Networks (RNN)(LSTM) + Embedding Layer <br>
  8.3 Model 3 : Recurrent Neural Networks (RNN)(GRU) + Embedding Layer <br>
  8.4 Model 4 : Recurrent Neural Networks (RNN)(Bi-LSTM) + Embedding Layer <br>
  8.5 Model 5: Feed-Forward Network + GloVe Embedding <br>
9. Results

## Experimentation Results
### Bag-of-Words (BoW) Experimentation

|  Model 	                  |  10-Fold CV Accuracy	    |
|-------------------------  |---	                      |
| Support Vector Machines  	|  67.9% 	                  |
| Multinomial Naive Bayes  	|  65.8% 	   	              |
| Logistic Regression  	    |  64.6% 	   	              |
| ADA Boosting  	          |  60.9% 	   	              |
| Random Forest Classifier  |  59.8% 	   	              |
| Gradient Boosting  	      |  59.0% 	   	              |
| XG Boosting  	            |  58.4% 	   	              |
| K-Nearest Neighbors  	    |  58.3% 	   	              |
| Decision Trees  	        |  51.7% 	   	              |

### TF-IDF Experimentation

|  Model 	                  |  10-Fold CV Accuracy	    |
|-------------------------  |---	                      |
| Multinomial Naive Bayes  	|  69.4% 	                  |
| Logistic Regression  	    |  68.8% 	   	              |
| Support Vector Machines  	|  68.4% 	   	              |
| K-Nearest Neighbors  	    |  65.2% 	   	              |
| ADA Boosting              |  61.0% 	   	              |
| Random Forest Classifier  |  60.5% 	   	              |
| Gradient Boosting  	      |  59.8% 	   	              |
| XG Boosting 	            |  58.9% 	   	              |
| Decision Trees  	        |  53.0% 	   	              |

### Deep Learning Experimentation

|  Model 	                                                                |  Accuracy	                  |
|-------------------------                                                |---	                        |
| Model 1 : Feed-Forward Network + Embedding Layer  	                    |  PENDING	                  |
| Model 2 : Recurrent Neural Networks (RNN)(LSTM) + Embedding Layer  	    |  PENDING 	   	              |
| Model 3 : Recurrent Neural Networks (RNN)(GRU) + Embedding Layer  	    |  PENDING 	   	              |
| Model 4 : Recurrent Neural Networks (RNN)(Bi-LSTM) + Embedding Layer  	|  PENDING 	   	              |
| Model 5 : Feed-Forward Network + GloVe Embedding                        |  PENDING 	   	              |
