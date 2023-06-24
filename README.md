# FaceID: One-Shot Classification Algorithm using Siamese Networks with Triplet Loss

Welcome to the FaceID Application powered by Siamese Networks with Triplet Loss. This deep learning algorithm is designed for face recognition, duplicate detection, and anomaly detection, among other applications. The implementation utilizes a Siamese network with three identical subnetworks to estimate the similarity between images, with Triplet Loss as the selected loss function. 

## Key Features

**More Robust to Class Imbalance**: Giving a few images per class is sufficient for Siamese networks to recognize those images in the future with the aid of one-shot learning.
**Advanced Face Recognition**: Utilize state-of-the-art deep learning techniques for accurate face recognition.
**Siamese Network Architecture**: Benefit from the unique structure of the Siamese network for effective feature extraction and similarity estimation.
**Triplet Loss Optimization**: Train the network using Triplet Loss, an effective loss function for learning discriminative feature embeddings.

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

## References

[FaceNet](https://arxiv.org/abs/1503.03832)

## Conclusion
Siamese networks with triplet loss are effective for one-shot face recognition tasks. This implementation can be used as a starting point for building a more robust face recognition system.
