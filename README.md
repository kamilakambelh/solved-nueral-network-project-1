Download Link: https://assignmentchef.com/product/solved-nueral-network-project-1
<br>
(Adaline, Back Propagation and Transfer Learning)




All data Is two dimensional ,  &lt;x,y&gt;   where    -1 &lt;= x, y &lt;= 1.  The data is all data points &lt;x, y&gt; where   x is of the form m/100 where m is an integer between -100 and +100  and y is of the form  n/100 with n an integer between -100 and +100.  Suppose that all data points with x &gt; 1/2 and y &gt;1/2  have the value 1; all other points have the value -1.

Now  suppose you do not know this; but you are given a random sample of data of size 1000 together with its value (e.g. the point  &lt;60/100,  80/100&gt; has value 1; while the point  &lt;20/100, 70/100&gt; has the value -1.




<strong>Part A. </strong>   Implement the Adaline learning algorithm and show how it generalizes to develop a decision that works on all the set.   Does the accuracy of the result depend on the training set?  Present tables and possibly a picture indicating your results.

Suppose the data is of the size n/10,000 with n an integer between -10,000 and +10,000.    How does this affect your choice of training data and testing data?




<strong>Part B:</strong>   Now change the problem so that points such that &lt;x.y&gt; has value 1 only if

1/2  &lt;= x**2 + y**2 &lt;= 3/4

What are the best results you obtain using an Adaline?   Does the quality of the results change if you use more data?  Present tables and perhaps a figure.

<strong>Part C:</strong>    Now try the same with a back-propagation algorithm instead of the adaline.

You will have to define the architecture (i.e number of neurons and number of levels)   You may either implement the algorithm or use a package.  BUT YOU WILL NEED TO LOOK INSIDE the results of each neuron separately for Part D

Show a geometric diagram in terms of the <strong>inputs </strong>of the training set for the <em>output</em> of <em>each neuron</em> <em>separately</em> in the neural network as well as for the output neuron.   Present tables of results both for training and testing.







<strong>Part D:</strong>   Now use the trained neurons from the next to last level of Part 3 as input and only an Adaline for the output.    (That is, you will give the adaline the output of the neurons from Part 3 in the level below the output,  and train only the Adaline.)

Describe how accurate the Adaline can be.  Give diagrams.




















