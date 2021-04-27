# Credit-Card-Fraud-Transactions

Credit card fraud can be defined as a case where someone uses someone else´s credit card for personal reasons while the owner and the card issuing authorities are unaware of the fact that the card is being used. 
In an era of digitalization, the need to identify credit card frauds is necessary. Fraud detection involves monitoring and analysing the behaviour of various users to perceive, detect or avoid undesirable actions. To perform credit card fraud detection effectively, there is a need to understand what is behind it.

This problem is particularly challenging from the perspective of learning, credit card fraud is usually associated with class imbalance. Imbalanced data typically refers to a problem with classification problems where the classes are not represented equally. In credit card fraud it is very common that the number of legitimate transactions far outnumber the ones that are considered fraudulent. 

Machine learning models are employed to analyse all the authorized transactions and report any suspicious activities. These reports are then investigated by professional who contact cardholders to confirm if the transaction performed was genuine or not. So, in hindsight, there is a need to train and update these models regularly to improve fraud-detection performance overtime.

Using machine learning to detect fraud is part of the wider effort of anomaly detection, which aims to identify rare events which differ significantly from most of the data. There are two main categories within anomaly detection:

- Unsupervised anomaly detection
- Supervised anomaly detection

Unsupervised techniques aim to detect anomalies in unlabelled datasets by grouping events according to their features. Clustering is a commonly used technique, and, more recently, autoencoders have also proven useful for feature extraction. The assumption here is that in each dataset where most events are non-fraudulent, the model will learn to reconstruct them better than anomalous ones and the reconstruction error will be higher for the outlier events.

Supervised techniques require the dataset to contain a label indicating whether an event is fraudulent or not. However, labelled datasets are limited, with only a few high-quality public datasets available. 

The methodology of this project is to use the latest machine learning algorithms to detect any anomalous activities by using a very popular dataset from Kaggle. 

Kaggle dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud
