# Non-linear Models for Supervised Learning

## Part I - Sentiment Analysis
### Approach 1 - Word Count Vectorization
#### Report 1

In this approach, we implemented a simple hand-crafted classifier that can label a
movie review as positive or negative.
Although simple, this algorithm takes a lot of time to execute (50 mins atleast)
depending on the size of the data which is not at all ideal.
Moreover, the accuracy that we got was also not upto the mark: 0.762

### Approach 2 - Neural Network Based Sentiment Classification
Here, we are going to solve the sentiment problem using a machine learning model
instead of a simple hand-crafted classifier. Then we’ll compare our results to determine
which approach is better
#### Report 2
Avg Training data accuracy: 0.92
Avg Test data accuracy:0.85
Q. Is it better or worse than your rule-based algorithm implemented in Approach 1?
As we can see, the avg accuracy we got using the neural networks for test data was
0.85. This accuracy is far greater than what we got with the approach 1. That is why
neural network models are preferred.
Another thing to note is that, the model reduced the execution time significantly.

#### Report 3
Here, we’ll test the neural network accuracies for different set of input values.

1. Increasing width
Conclusions: Increasing the width brought time down but also brought down the
accuracy to 0.75.

2. Increasing number of Epochs
Conclusions: Increasing the number of Epochs, increased the execution time
considerably as the number if iterations increased. But the accuracy of the system
increased significantly from 0.75 to 0.85

3. Increasing number of Epochs and width of hidden layers
Conclusions: By increasing both the number of epochs and the width, we
successfully increased the accuracy but the execution time was increased
drastically.

4. Increasing number of layers
Conclusions: Increasing the complexity of the model by adding more layers,
increased the accuracy as well as the execution time.

5. Increasing number of layers and width
Conclusions: Here, the layers and the width were increased. This made the
accuracy go high and time to go down.

6. Increasing number of layers and Epoch
Conclusions: When we increase the number of epochs, naturally the execution
time increases due to increase in the number of iterations. The accuracy
decreased, but not by much.

7. Increasing number of layers, epochs and width of the hidden layers.
Conclusions : Here, as we increased the width, the accuracy went down from 0.83
to 0.82.

8. Removing neutral words to compare the performance
Conclusion: When the neutral words are ignored, the accuracy went up from 0.82
to 0.85. While, the execution time increased because of the extra implementation
of removing the neutral words.

## Part II - Image Classification on the AI Quick Draw Dataset

Here, we are provided with a large dataset from the AI Quick draw tool. Firstly, we
studied the performance of a neural network (Multilayered Perceptron) having a single
layer. Next, we tried to increase the hidden layers to compare their accuracies. We also
studied the performance of the network when the resolution of the image changes.
The Code attached consists of the multilayered perceptron approach with 5 layers and
ignore words functionality implemented.

#### Report 4

1. Evaluation of the 2 hidden layer neural network

Output:
Test data accuracy: 0.24928
Time taken : 7160.738799571991

2. Compare the performance when the number of hidden layers are
increased to 3 and 5.

Output:
Test data accuracy: 0.23084
Time taken : 8926.286591
Conclusions: As you can see here, the accuracy went from 0.24928 to 0.23084
after adding one more layer to the neural network. Not a significant change, but
we can see that accuracy went down a bit.

## Final conclusions

The following graphs show the relationship between the layers in a perceptron model
with accuracy and execution time.
These graphs plotted by rounding off the values to nearest integer.

<img src = "https://github.com/vinita1005/ML/blob/non_linear_models/output/graph1.png" width="500" height="300">

The below bar graph is a plot of image resolution vs accuracy.
As you can see, one layered perceptron gives us better results with changes in image
resolution.

<img src = "https://github.com/vinita1005/ML/blob/non_linear_models/output/graph2.png" width="500" height="300">

The next graph gives us the plot for image resolutions vs execution time.
The one layered perceptron gives smaller execution time.

<img src = "https://github.com/vinita1005/ML/blob/non_linear_models/output/graph3.png" width="500" height="300">
