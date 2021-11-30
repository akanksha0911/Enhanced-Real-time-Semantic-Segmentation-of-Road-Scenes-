# Enhanced-Real-time-Semantic-Segmentation-of-Road-Scenes-
Enhanced Real-time Semantic Segmentation of Road Scenes — DDRNets

The official paper -https://paperswithcode.com/paper/deep-dual-resolution-networks-for-real-time


In artificial intelligence’s(AI) fantastic world, one of the many areas is Computer Vision which employs computers to derive meaningful information from digital images, videos, and other visual inputs and take actions or make recommendations based on that information. The agenda of this field is to enable machines to view the world as humans do. With the recent developments in the automotive vehicle industry, we have seen tremendous growth in securing the gap between the aptitudes of humans and machines. 

Computer Vision with Deep Learning advancements has been constructed and improved with time, primarily over one particular algorithm Convolutional Neural Network. A CNN breaks images down into pixels that are given tags or labels. The network starts with the input, which is the image. It is passed sequentially into Convolutional and Pooling layers. Then all Fully connected layers end with the output layer. There are three primary layers, of which the architecture of the convolutional neural network is built. 

The most general computer vision tasks that we frequently encounter in AI jargon include:
Image classification 
Object detection
Image segmentation- Semantic Segmentation and Instance Segmentation.

Here, I would like to address one particular task in Computer Vision called Semantic Segmentation and I will summarize Deep Dual-resolution Networks for Real-time and Accurate Semantic Segmentation of Road Scenes. 
Semantic Segmentation is a fundamental task in which each pixel of the input image should be assigned to the corresponding label. It plays an essential role in many practical applications, such as medical image segmentation, navigation of autonomous vehicles, and robots. 

One of the most challenging tasks humans do routinely is driving; hence autonomous driving is a complex activity that involves awareness, interpretation, and adjustment in real-time. In the age of artificial intelligence, one of the most actively researched areas is self-driving in the automotive industry, and we are still making sure if we can give the same ability to computers.
For fully autonomous vehicles, semantic Segmentation is a core element where neural networks need to output high-resolution feature maps of large receptive fields to deliver adequate results, which is computationally expensive. This problem is especially critical for scene parsing of autonomous driving to cover a wide field of view, and so far, all previous methods are very time-consuming.
To scale down this problem, paper proposed deep dual-resolution networks (DDRNets) which is composed of two main components: Bilateral networks with deep dual-resolution branches and multiple bilateral fusions are proposed for real-time semantic Segmentation as efficient backbones and the Deep Aggregation Pyramid Pooling Module extract multi-scale context information and merge them in a cascaded way. 
With standard test augmentation, DDRNet is comparable to state-of-the-art models and requires much fewer computing resources. The method achieves a new state-of-the-art trade-off between accuracy and speed on the Cityscapes and CamVid test sets. As per the paper, it is the first method to achieve 80.4% mIoU in nearly real-time (22 FPS) on Cityscapes only using fine annotations.
