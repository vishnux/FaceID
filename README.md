# One-Shot Face Recognition Algorithm using Siamese Networks with Triplet Loss

The Siamese Network with Triplet Loss is a deep learning algorithm which can be used for face recognition, duplicate detection, and anomaly detection etc. In this implementation, we use a Siamese network with three identical subnetworks to estimate the similarity between images.

## How it Works
The model is trained using triplets of images. A triplet consists of an anchor image, a positive image (which is similar to the anchor image), and a negative image (which is dissimilar to the anchor image). The goal of the model is to learn to differentiate between positive and negative images while keeping the distance between the anchor and positive images smaller than the distance between the anchor and negative images.

Once the model is trained, it can be used for one-shot face recognition. This means that given a single image of a person, the model can identify that person by comparing the features of the input image to those in the database.

## Requirements

* Python 3.x
* TensorFlow 2.x
* NumPy

## Usage

1) Clone this repository: git clone https://github.com/vishnux/Siamese-network-with-Triplet-Loss.git

2) Install the required packages

3) Run the jupyter notebook 

## Conclusion
Siamese networks with triplet loss are effective for one-shot face recognition tasks. This implementation can be used as a starting point for building a more robust face recognition system.
