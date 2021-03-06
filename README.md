# Fight delay predictor from a piori flightknowledge

Flight delays can be very frustrating to passengers and costly to airline companies. 
They arise from various factors such as the origin and destination airport, distance traveled, weather etc. 
All these variables makes the flight delay prediction a typical target for data mining techniques. 
This project compares two state-of-the-art machine learning algorithms, namely Random Forest and 
Gradient Boosting on the task of predicting flight delays on a priori flight knowledge. The dataset 
used are the 2007 entries from the US domestic flights database. After some standard dataset preprocessing 
and training we show that the best performing model is Gradient Boosting on the a priori knowledge with 
an R2 metric score of 0.1926. For the a posteriori knowledge the score on the same metric resulted in an 
expected, but astonishing 0.9990.

## The data used for this project are the 2007 entries from the US domestic flight database

https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
