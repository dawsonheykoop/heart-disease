# heart disease prediction
Trying to produce a model using a public data set "processed.cleveland.csv" from the UCI Machine Learning repository that has information regarding patients with attributes that could relate directly to heart disease.

This is an attempt of an ML project on my own. The process goes as follows...


## 1. Determining the right question
- what are the goals?
- what are the performance requirements?
- what data are we using?

Using the data from the UCI ML Repo, this model will predict whether or not a patient is likely to develop heart disease with 70% accuracy.


## 2. Preparing the data
This part is the most tedious and lengthy step of the entire process. It is said that most ML projects dedicate 80% of the total time on this part. For this project we are using pretty pristine heart disease data from the UCI ML Repository. There were a values that needed to be replaced but no more than a handful.


## 3. Selecting the correct algorithm
I selected first the Naïve Bayes classification algorithm. Many sources belive this algorithm is great for classification problems and is among the fastest algorithms offered in the scikit library. Luckily, the model trained with this algorithm was able to yield greater than 70% accuracy.


I used this as a way to get my foot in the door with data science and ML models. Thanks to the already pristine dataset given by the UCI ML Repo, the process was mostly painless. This model is a simple inital go at the problem, and could use much more verification and tweaking to improve it.
