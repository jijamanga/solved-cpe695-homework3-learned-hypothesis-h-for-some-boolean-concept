Download Link: https://assignmentchef.com/product/solved-cpe695-homework3-learned-hypothesis-h-for-some-boolean-concept
<br>
<strong><u>Question 1 (10 points):</u></strong>

Consider a learned hypothesis, <em>h</em>, for some Boolean concept. When <em>h</em> is tested on a set of 100 examples, it classifies 83 correctly. What is the standard deviation and the 95% confidence interval for the true error rate for <em>Error<sub>D</sub>(h)</em>?

<strong> </strong>

<strong><u>Question 2 (10 points)</u></strong><strong>:     </strong>

Consider again the example application of Bayes rule in Section 6.2.1 of Tom Mitchell’s textbook (or slide page 6 of Lecture 7). Suppose the doctor decides to order a second laboratory test for the same patient, and suppose the second test returns a positive result as well. What are the posterior probabilities of <em>cancer</em> and ¬<em>cancer</em> following these two tests? Assume that the two tests are independent.

<strong> </strong>

<strong><u>Question 3 – Programming (40 points):</u></strong>

In this programming problem, you will get familiar with building a neural network using backpropagation. You are supposed to implement the following steps:

<strong>Step 1:</strong> use our “titanic” dataset in homework #2, and split data in the same way you did in homework #2 as training and test sets;

<strong>Step 2: </strong>fit a neural network using independent variables ‘pclass + sex + age + sibsp’ and dependent variable ‘survived’. Omit all NA examples. Use 2 hidden layers and set the activation functions for both the hidden and output layer to be the <strong>sigmoid</strong> function. Set “solver” parameter as either <strong>SGD</strong> (stochastic gradient decend) or <strong>Adam</strong> (similar to SGD but optimized performance with mini batches). You can adjust parameter “alpha” for regularization (to control overfitting) and other parameters such as “learning rate” and “momentum” as needed.

<strong>Step 3:</strong> check the performance of the model: in-sample and out-of- sample accuracy, defined as            in-sample percent survivors correctly predicted (on training set)  in-sample percent fatalities correctly predicted (on training set)  out-of-sample percent survivors correctly predicted (on test set)  out-of-sample percent fatalities correctly predicted (on test set)

CPE/EE 695 Applied Machine Learning               Homework#3                                                                   Spring 2019

Please try few network structures (i.e., number of neurons at each hidden layer) and show their respective accuracy.

<strong>Step 4: </strong>compare the in-sample and out-of-sample accuracy (as defined in step 3) with the pruned decision tree obtained in homework #2. (You can either use a table or a figure to compare the accuracy of the two learning algorithms)




<u>Note: There are two options to implement the neural network</u>:

<strong>Option 1:</strong> use scikit-learn library;

Here is the tutorial: <u>http://scikit-learn.org/stable/modules/neural_networks_supervised.html</u>

<strong>Option 2:</strong> implement backpropagation yourself; in your implementation, you better set the following:

<ul>

 <li>the initial weights to be uniformly between [-0.1, +0.1]</li>

 <li>the learning rate to be 0.3 or 0.5</li>

 <li>the number of iterations to be at least 5000 or even more</li>

</ul>




You can choose either option for this homework. No matter what you choose, make sure you know how to update the weights.

















