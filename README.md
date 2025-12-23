# Image Processing & Computer Vision

> Project work for the "Image Processing and Computer Vision" course at Alma Mater Studiorum - University of Bologna.

**Authors**

* Dotti Andrea [[_Github profile_](https://github.com/AndreaD002)][[_Institutional_ _email_](mailto:andrea.dotti4@studio.unibo.it)]

* Petrelli Tommaso [[_Github profile_](https://github.com/petrello)][[_Institutional_ _email_](mailto:tommaso.petrelli2@studio.unibo.it)]
---

## Assignment 1 - Multiple Books Detection System based on Scale-Invariant Features Matching

We design and implement a complete traditional Computer Vision pipeline capable of detecting multiple instances of books on a shelf, starting from their corresponding reference model images. The objective is to identify, for each book model, all occurrences in a scene image represented by bounding boxes identified by the corners' coordinates and area.

Our approach is entirely based on local invariant features and geometric verification. The core idea is that each book cover or spine contains unique visual patterns that produce distinctive keypoints. By detecting and matching these keypoints across model and scene images, we can establish robust correspondences and estimate the geometric transformation that maps the model onto the scene.

---

## Assignment 2 - Deep Learning-Based Image Classification

We study deep learning approaches for fine-grained image classification on the Oxford-IIIT Pet Dataset, which comprises 37 breeds of cats and dogs. The objective is to analyse both training-from-scratch and transfer learning strategies, with a focus on accuracy, generalisation, and training stability.

### Part 1 – Custom CNN network
We design a lightweight convolutional neural network inspired by EfficientNet principles, emphasising parameter efficiency. The architecture integrates depthwise separable convolutions, residual connections, stochastic depth, and regularisation techniques. A systematic ablation study is conducted to quantify the impact of individual components on performance.

### Part 2 - Fine-tuning a pretrained ResNet-18
We fine-tune a ResNet-18 pretrained on ImageNet-1K using a three-stage gradual unfreezing strategy. The classifier is trained first, followed by progressive unfreezing of high-level backbone layers with carefully tuned hyperparameters and data augmentation.
