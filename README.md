# cs324-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS324 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs324-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98438&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS324 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
CS324

Assignment 1

1 Part I: the perceptron

In this first task you’re asked to implement and test a simple artificial neuron: a perceptron (see perceptron- slides.pdf ).

1.1 Task 1

Generate a dataset of points in R2. To do this, define two Gaussian distributions and sample 200 points from each. Your dataset should then contain a total of 400 points, 200 from each distribution. Keep 160 points per distribution as the training (320 in total), 40 for the test (80 in total).

1.2 Task 2

Implement the perceptron following the specs in perceptron.py and the pseudocode in perceptronslides.pdf. 1.3 Task 3

Train the perceptron on the training data (320 points) and test in on the remaining 80 test points. Compute the classification accuracy on the test set.

1.4 Task 4

Experiment with different sets of points (generated as described in Task 1). What happens during the training if the means of the two Gaussians are too close and/or if their variance is too high?

2 Part II: the mutli-layer perceptron (65 points)

In this second part of Assignment I you’re asked to implement a multi-layer perceptron using numpy. Using scikit- learn and the make moons method1, create a dataset of 2,000 two-dimensional points. Let S denote the dataset, i.e., the set of tuples {(x(0),s,ts)}Ss=1, where x(0),s is the s-th element of the dataset and ts is its label. Further let d0 be the dimension of the input space and dn the dimension of the output space. In this assignment we want the labels to be one-hot encoded2. The network you will build will have N layers (including the output layer). In particular, the structure will be as follows:

• Each layer l = 1,··· ,N first applies the affine mapping

x ̃(l) =W(l)x(l−1) +b(l),

1 https://scikit- learn.org/stable/modules/generated/sklearn.datasets.make_moons.html#sklearn.datasets.make_moons 2Remember to transform the original dataset labels using one-hot encoding https://en.wikipedia.org/wiki/One-hot

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
•

2.1

</div>
<div class="column">
Note that both max and exp are element-wise operations.

Finally, compute the cross entropy loss L between the predicted and the actual label,

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
where W(l) ∈ Rdl×d(l−1) is the matrix of the weight parameters and b(l) ∈ Rdl is the vector of biases. Given x ̃(l), the activation of the l-th layer is computed using a ReLU unit

x(l) = max(0, x ̃(l)).

The output layer (i.e., the N-th layer) first applies the affine mapping

x ̃(N) =W(N)x(N−1) +b(N),

and then uses the softmax activation function (instead of the ReLU of the previous layers) to compute a valid

</div>
</div>
<div class="layoutArea">
<div class="column">
probability mass function (pmf)

</div>
</div>
<div class="layoutArea">
<div class="column">
Task 1

</div>
</div>
<div class="layoutArea">
<div class="column">
x(N) = softmax(x ̃(N)) = exp(x ̃(N)) . 􏰝dN exp(x ̃(N ) )i

i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
L(x(N), t) = − 􏰕 ti log x(N). i

i

</div>
</div>
<div class="layoutArea">
<div class="column">
Implement the MLP architecture by completing the files mlp numpy.py and modules.py. 2.2 Task 2

Implement training and testing script in train mlp numpy.py. (Please keep 70% of the dataset for training and the remaining 30% for testing. Note that this is a random split of 70% and 30% )

2.3 Task 3

Using the default values of the parameters, report the results of your experiments using a jupyter notebook where you show the accuracy curves for both training and test data.

3 Part III: stochastic gradient descent (15 points)

In this third part of Assignment I, you will implement an alternative training method in train mlp numpy.py based on stochastic gradient descent.

3.1 Task 1

Modify the train method in train mlp numpy.py to accept a parameter that allows the user to specify if the training has to be performed using batch gradient descent (which you should have implemented in Part II) or stochastic gradient descent.

3.2 Task 2

Using the default values of the parameters, report the results of your experiments using a jupyter notebook where you show the accuracy curves for both training and test data.

</div>
</div>
</div>
