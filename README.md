# MNIST classification using only numpy

### Key
-> weight_sum = input_vector * weight_vector.T + bias 
-> backpropagation = gradient descent
-> gradient clipping (using L2 norm) => for handle exploding gradient problem

### method for training model 
-> batch training
-> early stopping (if abs(training_acc - validation_acc) >= trashold
