# CIFAR-10 Dataset
The CIFAR-10 and CIFAR-100 are labeled subsets of the 80 million tiny images dataset.
They were collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton.
see http://www.cs.toronto.edu/~kriz/cifar.html

Contains 6 files, each with 10000 shuffled images of 10 labeled classes.

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

> The files are pickles (python2) with keys ```['data', 'labels', 'batch_label', 'filenames']```

## Start Neural Networks training:
- Fully Connected Neural Network (simple neural network + with regularization)
- Convolutional Neural Network (few convolutional layers + fully connected layers)

### Fully-connected network
Train a **fully-connected network** to reconstruct the energy of a cosmic-ray-induced air shower.  

<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/cifar_tutorial//blob/master/fully_connected.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>

### Convolutional neural network
Train a **convolutional neural network** to reconstruct the energy of a cosmic-ray-induced air shower.  

<a target="_blank" rel="noopener noreferrer" href="https://colab.research.google.com/github/jglombitza/cifar_tutorial//blob/master/convolutional.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="drawing" width="180"/> </a>
