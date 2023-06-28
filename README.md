# automated_selie_system
Automated Selfie System is a Python-based project that utilizes computer vision and deep learning techniques to capture selfies automatically. When we run the code the detects smile using LENET 5 architecture in the backend. Capture selfies effortlessly and hands-free. User-friendly, convenient, and fun.

**DATASET DESCRIPTION**
The GENKI4K dataset is used for smile detection, containing 4000 images with 2126 smiling and 1838 non-smiling images.

The proposed smile detection system in the research paper includes GFE, LBP, data amalgamation using autoencoder, and KSOM-based classifier.

GFE extracts geometric features from facial regions like eyes, nose, eyebrows, and lips.

LBP feature extraction labels pixels based on their neighborhood to capture texture indicators.

Autoencoder is used for feature vector compression and improved feature representation.

KSOM is a neural network algorithm used for clustering complex datasets and visualizing high-dimensional data.

The dataset used in the project has 13241 images, with 9213 non-smiling and 4028 smiling images.

Class weight and class total are used to handle the dataset's skew and make the model understand the class imbalance.

Pre-processing steps include standardizing the images to 28x28 size and converting them to grayscale for better CNN detection.

Grayscale is preferred for CNN as it simplifies the detection of faces and smiles.

**PROPOSED METHODOLOGY**

After conducting research, I found that the LeNet architecture is the most suitable choice for the automated selfie system project. Compared to other complex and high-weighted architectures, LeNet offers a simpler and lightweight solution. LeNet-5, proposed by Yann LeCun and his team in 1998, was originally designed for document recognition, specifically for recognizing handwritten and machine-printed characters. The architecture gained popularity due to its effectiveness and straightforward design. One of the key advantages of LeNet is its simplicity. It is a multi-layer convolutional neural network (CNN) primarily used for image classification tasks. The architecture comprises a series of convolutional layers, pooling layers, and fully connected layers. By utilizing LeNet in the automated selfie system, the model can effectively detect smiles in real-time. The system captures the input frame, resizes it, and converts it to grayscale. The face detector cascade is then applied to identify faces within the frame. The detected regions of interest (ROIs) are further processed and resized to a fixed dimension. These ROIs are fed into the LeNet model for smile classification. The LeNet model, being lightweight, allows for efficient processing and quick detection of smiles. It provides a balance between accuracy and computational efficiency, making it ideal for real-time applications such as the automated selfie system. In conclusion, the LeNet architecture, particularly LeNet-5, is a well-suited choice for the automated selfie system project due to its simplicity, lightweight nature, and effectiveness in image classification tasks.

**THE PROPOSED MODEL RESULTS**
This is how we can see the image when we trained the model and runs it. 
![image](https://github.com/nikhil-188/automated_selie_system/assets/84719583/024de409-f8fd-425a-9d8d-68b15750ad8f)

This is how the pictured get stored when we smile and the system will detect the smile.
![image](https://github.com/nikhil-188/automated_selie_system/assets/84719583/3d15a0fe-e453-4caf-9b85-1a871400331e)
