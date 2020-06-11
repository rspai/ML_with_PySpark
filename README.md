# ML_with_Spark
Predictive analytics with Spark

This project implements a movie genre prediction model using Apache Spark.
train.csv has movie summaries of around 31K movies along with their genres.
test.csv has just plot summaries, on which genres are to be predicted.

The task of predicting the genre is essentially a <bold>multi-label classification</bold> problem. 
A movie can have multiple genres associated with it. The model should be able to predict all the genre associated with the movie.
