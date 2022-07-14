# naive-bayes-formula-example
(Hobby) Here is an example for the naive bayes formula. Everyone will understand it. :) 

Assume binary random variables (street wet / street dry) and (raining / not raining). And 
the events: 
```
A = "street wet" 
B = "raining" 
```
Assume we know 
```
P(A | B) = 0.99 
P(A) = 0.2
P(B) = 0.1 
```
P(A | B) = .99 is very high. This means: When it is raining, the street is wet with a probability of 99%. 
We all know, when it rains, the street usually becomes wet. 


The Bayes formula is now given by: 
```
P(B | A) = P(A | B) * P(B) / P(A) = 0.99 * 0.1 / 0.2 = 0.495. 
```
This means: When the street is already wet, the probability that it is raining right now is given by 49.5%. 
