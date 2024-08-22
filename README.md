##### Link to air shower example (regression) --> https://github.com/jglombitza/tutorial_nn_airshowers

# CIFAR-10 Dataset
The CIFAR-10 and CIFAR-100 are labeled subsets of the 80 million tiny images dataset.
They were collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton.
see http://www.cs.toronto.edu/~kriz/cifar.html

The images are of size 32x32 pixels with 3 color channels (RGB).
The intensity in each channels is encoded as unsigned 8-bit integers 0...255.
<ol start="0">
  <li>airplane</li>
  <li>automobile</li>
  <li>bird</li>
	<li>cat</li>
  <li>deer</li>
  <li>dog</li>
	<li>frog</li>
  <li>horse</li>
  <li>ship</li>
	<li>truck</li>
</ol>

## Start Neural Networks training:
- Fully Connected Neural Network (simple neural network + with regularization)
- Convolutional Neural Network (few convolutional layers + fully connected layers)
- Convolutional Neural Network (few tranformer layers + fully connected layers)

### Fully-connected network
Train a **fully-connected network** to classify images of the CIFAR-10 dataset.  

<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/cifar_tutorial//blob/master/fully_connected.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>

### Convolutional neural network
Train a **convolutional neural network** to classify images of the CIFAR-10 dataset.   

<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/cifar_tutorial//blob/master/convolutional.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>

### Vision transformer
Train a **transformer network** to classify images of the CIFAR-10 dataset.

<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/cifar_tutorial/blob/main/vision_transformer.ipynb
"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>
