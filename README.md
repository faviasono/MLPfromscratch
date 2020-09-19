# MultiLayerPerceptron
During the Data Mining course at Eindhoven University I had to implement a **MLP** from scratch to perform a binary classification problem.


The architecture can be arbitrarily modified (i.e. number of neurons in each layer and number of layers).
For the hidden layers I used the **Relu** activation function and for the output layer a **simgoid** function to compute a probability distribution.

You must use for each layer an activation function. 
In the program there are only the definitions of Relu, LRelu and Sigmoid, therefore if you want to try different activation functions you must implement them.
This is also true for the loss functions since I have used the MSE cost functions.

## Usage

In the main section you cam define your architecture as shown below.
  
<pre><code class="python"># 
nn_architecture = {
                  'layers':[(10,2),(10,10),(1,10)],
                  'activations':[relu,relu,sigmoid]
                   }
</code></pre>



