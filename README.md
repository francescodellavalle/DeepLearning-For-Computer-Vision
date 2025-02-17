# DeepLearnig
Image Recognition project, Universidad Politecnica de Madrid.

Goals:
• Develop proficiency in using Tensorflow/Keras for training Neural Nets (NNs).
• Put into practice acquired knowledge to optimize the parameters and architecture of a feed-forward Neural Net (ffNN), in the context of an image recognition problem.
• Put into practice NNs specially conceived for analysing images. Design and optimize the parameters of a Convolutional Neural Net (CNN) to deal with previous image classification task.
• Train popular architectures from scratch (e.g., GoogLeNet, VGG, ResNet, ...), and compare the results with the ones provided by their pre-trained versions using transfer learning.

Image recognition is crucial in computer vision, as it involves recognizing and categorizing
objects, scenes, or patterns in digital images or video frames. Its significance resonates
across diverse real-world applications, spanning autonomous driving, medical diagnosis,
surveillance, and augmented reality.
The heart of image recognition lies in creating algorithms that can understand and interpret
the complex visual information contained within images. Traditional methodologies heavily
leaned on manually crafted features and shallow machine learning models, often grappling
with the complexities inherent in visual patterns and the variability introduced by lighting
conditions, viewpoints, and background clutter.
However, with the emergence of deep learning, particularly convolutional neural networks
(CNNs), substantial strides have been made in the domain of image recognition. By
traversing multiple layers of convolution, pooling, and non-linear transformations, CNNs
adeptly extract increasingly abstract features, thereby facilitating precise recognition of
objects and patterns depicted in images.
However, despite these remarkable advancements, image recognition still presents
significant challenges due to factors such as occlusions, variations in scale and orientation,
and the presence of multiple objects within a single scene

------------------
We started our journey with feed-forward Neural Nets (**ffNN**), traversed through
Convolutional Neural Nets (**CNNs**), and culminated by **training popular architectures from
scratch** using transfer learning. Beginning with dataset analysis, we meticulously evaluated
our network performances on the testing dataset, fine-tuning hyperparameters to enhance
results. Ultimately, we achieved notable outcomes, experimenting with various networks to
enrich our analysis.
Our most promising results were achieved as follows: ffNNs yielded the best performance in
the second experiment, CNNs excelled in the initial experiment, and regarding Transfer
Learning, the final experiment showcased superior results. Additionally, it's worth noting that
the performance across Transfer Learning experiments could potentially have been further
improved if not for the stringent computational limitations we faced. Especially, we would
have likely addressed the misclassification issue related to the "Helicopter" class had we
been afforded more epochs for training in the Transfer Learning experiments. As we did,
focusing on data augmentation for a particular class, such as the "Helicopter" class, could
have been a strategic decision. This approach involves augmenting the available data for
that specific class by applying transformations such as rotation, scaling, or flipping.
