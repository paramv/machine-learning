## Supervised Learning
* Example - 1: Problem of selling house. Plot a area vs cost graph.
* Find the cost of given house based on 1. a straight line 2. a quadratic 3. polynomial
* Regression - predict contniuous value ouput
* Example - 2 : Predicting breast cancer malignancy based on tumor size. 
* This is a discrete OR classification problem because there can only be two values O - benign and X-malignant. 
* Support Vector Machines - a mathematical trick to narrow down an infinite set of chars (like age, tumor size, clump thickness etc) to a finite set

## Unsupervised Learning
* Clustering algorithm - automatically structure data without giving any specifics. Google News uses clustering, 
	* putting machines together in a cluster in datacenters 
	* social networking - automatically create groups
	* market segmentation
	* astronomical data analysis

## Note : Use octave/matlab for quick prototypes

## Linear Regression with One Variable 
* PS : 0 =. theta
* AKA Univariate linear regression
* Lets say we have values of y for a given value x; our hypothesis function is of type
h0(x) = 0o + 01*x where 0o and 01 are constants whose value we must determine.
* Cost function J- Mean squared error
i.e., 1/2m Sum(i->1 to m) (h0(xi) - yi)^2
this basically gives a means to compare the difference between actual results and predicted ones to arrive at an error factor
* Gradient descent - this is used to plot the values of 0o and 01 vs the cost function. When the cost hits 0, we know that we've predicted the exact solution
* Simplified hypothesis is when 0o = 0, therefore h(x) = 01x
* J01 = h01(x); for univariate regression minimising J01 gives the best possible solution
* Gradient descent - use simultaneous update always
* Batch gradient descent - since we sum the mean squared error over all m training sets, its called "batch"
* Gradient descent is "iterative" because it starts at one point and moves towards convergence
* VVVIP:- it is impossible to "perfectly" predict anything with supervised learning
* Use only 1 indexed vectors unless specified otherwise
