Project Overview:
Crowd counting and density estimation are crucial tasks in computer vision with applications in public safety,
traffic monitoring, event management, and urban planning. The objective is to estimate the number of people present
in a given image and to generate a density map that visually represents crowd concentration across different regions of the image.
This project presents a deep learning-based pipeline that processes input images and outputs two key predictions: a total crowd count and a density map. 
The model is trained on benchmark datasets such as ShanghaiTech and UCF_CC_50, using convolutional neural networks 
(CNNs) to learn spatial features and patterns that correlate with human presence.

🎯 Goals:
The main goals of this project are:
----To build an accurate and efficient model for counting people in images.
----To generate density maps that help visualize crowd distribution.
----To support both training from scratch and inference using pre-trained weights.
----To provide clear and reusable code that can be adapted to new datasets or improved models.

🧠 Methodology:
The approach is based on deep CNN architectures that learn to regress crowd density maps from raw images.
The predicted density map is then integrated to obtain the total count. The model is optimized using mean squared 
error loss between the predicted and ground truth density maps. Techniques like data augmentation 
and batch normalization are employed to improve generalization.
