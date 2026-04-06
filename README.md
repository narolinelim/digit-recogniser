# Digit Recogniser with Convolutional Neural Networks (CNNs)
## CNN Architecture
CNN architecture is adapted from the VGG architecture.  
### 1. Block 1 and 2
- 2 convolutional layers
- 2x2 max-pooling layer
- 25% neuron dropout

### 2. Block 3
- Dense layer of size 128
- 50% neuron dropout
- Dense layer of size 10 for each number
