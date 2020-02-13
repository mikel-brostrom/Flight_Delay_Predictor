# Fight delay predictor from a piori flightknowledge

Flight delays can be very frustrating to passengers and costly toairline companies. 
They arise from various factors such as theorigin and destination airport, distance traveled, weather etc. 
All these variables makes the flight delay prediction a typical targetfor data mining techniques. 
This project compares twostate-of-the-art machine learning algorithms, namely RandomForest and 
Gradient Boosting on the task of predicting flightdelays on a priori flight knowledge. The dataset 
used are the 2007entries from the US domestic flights database. After somestandard dataset preprocessing 
and training we show that the bestperforming model is Gradient Boosting on the a priori knowledge with 
an R2 metric score of 0.1926. For the a posteriori knowledgethe score on the same metric resulted in an 
astonishing 0.9990.

## The data used for this project is the 2007 entries from the US domestic flight database

https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
