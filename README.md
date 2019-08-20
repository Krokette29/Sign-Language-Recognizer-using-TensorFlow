# Sign Language Recognizer using TensorFlow
 This project recognizes sign language from 0 to 5, which uses basic structure of TensorFlow, modified from deeplearning.ai.

```
number of input: 12288
number of classes: 6
number of training examples: 1080
number of test examples: 120
```

```
shapes of parameters:
W1 : [25, 12288]
b1 : [25, 1]
W2 : [12, 25]
b2 : [12, 1]
W3 : [6, 12]
b3 : [6, 1]
```

```
number of epochs: 3000
mini-batch size: 32
lambda of L2 Regularization: 0.2
learning rate: 0.0001
optimizer： Adam
```

```
Final results:
Train Accuracy: 0.9777778
Test Accuracy: 0.84166664
```
