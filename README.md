# Federated Deep Learning Classification Using MNIST


## Description
Train subsets of the MNIST handwritten digit dataset using the same structure of deep learning neural network, gather trained parameters and average them to obtain new initial parameters and feed back to each sub-network, repeat training to obtain approximately the same parameters in all the subsets


## Questions to Explore
How is the performance of this distributed training algorithm compare to traditional deep learning neural network in terms of accuracy and speed?


Considering real life scenario where different devices provide different amount of examples to the training, how would subsets with different sizes affect training compared to same-sized subsets?


(optional) For communication efficiency, how would the subset-to-central parameter update frequency affect the speed of training, and how to balance speed and the communication cost of transmission


(optional) Considering real life situation when users may have bad connection, only parts of the parameters of a model are delivered to the central server, how would this affect the accuracy and efficiency of model training and how should adverse impact be minimised.


(optional) Implement this structure with Dr Zhou’s federated learning algorithm instead of deep learning neural networks for the subset training


## Things to Consider


each subset should at least contain 2 different numbers, or each subset should contain all 10 numbers


size of subset


think about more factors that affects the efficiency and speed of training


## To-do
[ ] write code for neural network for training each subset


[ ] establish the distributed federated learning structure


[ ] experiment with different factors and collect results


[ ] visualise results and write up conclusion
