# Image-Segmentation-U-Net

Welcome to the Image Segmentation with U-Net project! In this repository, you will build a U-Net, a specialized Convolutional Neural Network (CNN) designed for precise image segmentation. You will use it to predict labels for every pixel in an image, particularly focusing on images from a self-driving car dataset.

## Problem Statement

Semantic image segmentation is a type of image classification that labels each pixel in an image with its corresponding class. It goes beyond object detection by providing a pixel-perfect understanding of the environment. This level of detail is crucial for self-driving cars to navigate safely.


## U-Net

U-Net, named for its U-shape, was initially created for tumor detection but has become popular for various semantic segmentation tasks. It improves upon the Fully Convolutional Network (FCN) architecture by introducing skip connections and transposed convolutions.

### Model Details

U-Net consists of two main components:

1. Contracting Path (Encoder):
   - Multiple convolutional layers reduce image dimensions.
   - Each downsampling step doubles the number of feature channels.
   - Skip connections capture fine information and prevent information loss.

2. Expanding Path (Decoder):
   - Upsampling steps increase image dimensions.
   - Transposed convolutions reverse downsampling.
   - Cropping ensures compatibility with the contracting path.
   
In the final layer, a 1x1 convolution maps feature vectors to the desired number of classes, one layer per class.

U-Net includes a total of 23 convolutional layers.

### Model Benefits

- U-Net excels in semantic image segmentation.
- Skip connections retain fine details.
- Transposed convolutions reverse downsampling.
- Information loss and overfitting are minimized.
![image](https://github.com/meliikaa/Image-Segmentation-U-Net/assets/111120849/f303f4fe-9670-4726-8796-2e1b886ffe11)


## Conclusion

By completing this project, you will acquire valuable experience in image segmentation using U-Net. You'll understand the crucial role of semantic image segmentation in self-driving cars and learn to apply sparse categorical cross-entropy for pixel-wise prediction. Dive into the world of precise image understanding and enjoy building your own U-Net model. If you have questions or need assistance, feel free to reach out to the project contributors or the community. Happy coding!

![Image Segmentation](images/image_segmentation.png)

#ImageSegmentation #SemanticSegmentation #UNet #DeepLearning #ComputerVision #MachineLearning #ProgrammingAssignment
