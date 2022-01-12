## **EM Algorithm - Clustering**

To run the jupyter notebook following libraries are needed:
●	 pandas\
●	 NumPy\
●	 matplotlib\
●	 Sklearn\
●	 SciPy

Apart from this, I have also uploaded the data file seeds_data.txt, which should be present in the same directory as the notebook and the same data file should be used, as errors in some rows of the data have been fixed by me.


### **Advantages of EM(Expectation-Maximization) - algorithm for clustering:**

●	The clusters are not limited to a particular shape and can change according to the probability distribution.\
●	Using EM, we can constrain the algorithm for specified values of covariance matrices which can help us to have good control on the shape of our clusters.\
●	Using EM - algo we can also Identify subpopulations in the data having different characteristics.\
●	Implementation of this algorithm is simpler as compared to various other algorithms out there.\
●	This algorithm can also be used when some data values are missing.\
●	Because of the simplicity of the implementation of the algorithm, the whole algorithm can be parallelized easily.

### **Disadvantages of EM algorithm:**
	
●	Sometimes, it can be very computationally expensive task and the convergence of the algorithm might be very slow rendering this algorithm useless in many real-world scenarios\
●	Sometimes the solution may stuck in the local optimum, which is a very big problem.

●	The EM algorithm requires an initial estimate of the parameters, so the quality of the solution is greatly affected by the quality of the initial estimates. And keeping in mind the slowness of the convergence of the algorithm, the stopping criterion should also be chosen with utmost care.


**Solution for the disadvantage of being stuck in local optima:**

One of the tested solutions which lead to a good and promising result is to repeat several times from different initialization points. Although it increases the computation time but like various other statistical and machine learning algorithms, there is a tradeoff between computation time and accuracy.


**Solution for the problem of selecting good initial estimates of the parameters:**

This solution is common for almost all numerical optimization methods, it is highly recommended and encouraged to try various initial starting points. Then select the best results among all of the results.


