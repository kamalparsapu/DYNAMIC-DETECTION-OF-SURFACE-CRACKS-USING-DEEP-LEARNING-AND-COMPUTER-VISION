# DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION
Welcome to the Crack Detection deep learning and computer vision techniques for crack detection in structural elements. We have employed three state-of-the-art deep learning architectures: ResNet v2, VGG16, and Xception, along with transfer learning, to classify surface cracks with high accuracy.This project focuses on leveraging deep learning techniques to detect cracks in infrastructure, such as roads, bridges, and buildings. Cracks pose a significant risk to structural integrity and safety, and automated detection systems can help identify and address these issues promptly.

![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/blob/main/8th%20sem%20major%20project%20report%202/tested-1%20(1).png)

## Abstract

Detecting cracks in infrastructure is essential for ensuring safety and preventing potential disasters. This project aims to develop a deep learning model capable of accurately identifying and classifying cracks in images. By employing various deep learning architectures, including ResNet, VGG, and Inception, and transfer learning techniques, we aim to create an efficient and robust crack detection system.

## Model Architecture

For this project, we explored three different deep learning architectures: ResNet, VGG, and Inception, as the backbone for our crack detection models.

1. **ResNet**: Residual Network (ResNet) is a deep convolutional neural network architecture known for its ability to effectively train very deep networks. By leveraging pre-trained weights from the ResNet model, we can accelerate training and improve performance on our crack detection task.

   ![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/assets/101061373/eff71762-cb9c-4bf3-8491-1955b501cb29)


2. **VGG**: The Visual Geometry Group (VGG) network architecture is characterized by its simplicity and uniform architecture. It consists of a series of convolutional layers followed by max-pooling layers and fully connected layers. We utilized the VGG architecture to train a crack detection model and evaluate its performance.

   ![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/assets/101061373/87b4886d-0d74-4222-bb67-b054e875fe53)


3. **Inception**: The Inception architecture, also known as GoogLeNet, is designed to achieve better accuracy and efficiency in image recognition tasks. It consists of multiple inception modules, which incorporate multiple filter sizes and pooling operations in parallel. We investigated the Inception architecture for crack detection and compared its performance with other architectures.

  ![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/assets/101061373/89c01681-c5be-497f-9a87-739409352265)


## Dataset

The dataset used for training the crack detection models consists of images captured from various sources, including drones, cameras, and satellite imagery. These images contain different types of cracks, such as surface cracks, structural cracks, and pavement cracks. The dataset is labeled with ground truth annotations, indicating the presence and location of cracks in each image.

Sample images from the dataset:
![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/blob/main/project%20related%20images/download%20(1).png)

## Performance

Each of the trained models achieved an accuracy of 99.99927% on the test dataset, demonstrating their effectiveness in detecting cracks in images. Further evaluation metrics, such as precision, recall, and F1 score, are provided in the project documentation.
- *Confusion matrix comparision* :
  ![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/blob/main/project%20related%20images/download%20(14).png) 
  
- *Metrics Comaprision* :

  ![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/blob/main/8th%20sem%20major%20project%20report%202/WhatsApp%20Image%202024-04-29%20at%2011.40.40%20AM.jpeg)


## Technologies Used

1. Python
2. TensorFlow
3. Keras
4. OpenCV
5. Google Colab

   
## Project Demonstration 
[![Demonstartion](thumbnail_image_url)](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/assets/101061373/8959afde-0b92-43ee-9ae8-794d1258cb5c)


## Tested Sample Images

Real-time crack detection was performed using the trained models on sample images captured from different environments. The models successfully identified cracks in these images, as shown below:

![image](https://github.com/kamalparsapu/DYNAMIC-DETECTION-OF-SURFACE-CRACKS-USING-DEEP-LEARNING-AND-COMPUTER-VISION/blob/main/8th%20sem%20major%20project%20report%202/tested-1%20(2).png)


## References
- (https://www.engineeringcivil.com/types-of-cracks-in-concrete-and-their-causes.html)
- (https://www.ultratechcement.com/for-homebuilders/home-building-explainedsingle/descriptive-articles/understanding-the-types-of-cracks-in-concrete)
-(https://indianrailways.gov.in/railwayboard/uploads/directorate/eff_res/camtech/Civil%20E)
- (https://www.kaggle.com/code/paulopinheiro/surface-crack-detection-100-accuracy#GradCam)
- (https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.newsgram.com%2Faccidents%2F2023%2F01%2F16%2Fjoshimath-landslide-cracks-appear-in-44-more-buildings-in24hrs-including-pwds-resthouse&psig=AOvVaw3i4adGEPvJkIZBUNWX1Ktv&ust=1701770504999000&source=images&cd=vfe&opi=89978449&ved=0CBQQjhxqFwoTCICk9MnD9YIDFQAAAAAdAAAAABAJ)

Feel free to explore the code and documentation provided in this repository for detailed insights into the crack detection project!

**Stay Safe and Crack-Free!**
