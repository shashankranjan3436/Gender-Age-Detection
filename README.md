# INTRODUCTION
The process of upgrading images taken from various sources, such as satellites, airplanes, and cameras, is called picture processing. It involves analyzing and calculating the data resulting from the image. Before it can be properly studied and imagined, the digital pictures need to be carefully crafted.
The location of the information in the pictures is very important to researchers. This is why the data collected during the processing process is analyzed and adjusted for discovery.
Different procedures are also involved in the processing of facial images. In a facial identification strategy, the data collected by the faces are analyzed to determine the characteristics of the person. At any point, the individual can associate with the other person.
The evolving of ideas helps in figuring certain boundaries. Age assessment is a multi-class issue in which the years; are categorized into classes. Individuals of various ages have various facials, so it is hard to assemble the pictures.
To identify the age and gender of several faces’ procedures, are followed by several methods. From the neural network, features are taken by the convolution network. In light of the prepared models, the image is processed into one of the age classes. The highlights are handled further and shipped off the preparation frameworks.

# DATASET
Here Adience dataset will be used; the dataset is [CLICK HERE](https://drive.google.com/drive/folders/1tqd1XDxB-W1X0kAVjiotCudPAKTiI3iS?usp=sharing). This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 26,580 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 1GB in size. The models we will use have been trained on this dataset.
# CNN Architecture
The convolutional neural network for this python project has 3 convolutional layers:

- Convolutional layer; 96 nodes, kernel size 7
- Convolutional layer; 256 nodes, kernel size 5
- Convolutional layer; 384 nodes, kernel size 3
It has 2 fully connected layers, each with 512 nodes, and a final output layer of softmax type.

To perform this project, we have done following things:

- Detect faces
- Classify into Male/Female
- Classify into one of the 8 age ranges
- Put the results on the image and display it
