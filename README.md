# NecklineClassifier

The primary goal of this project is to classify different types of necklines in fashion images using deep learning models. The project includes:  

**CNN_MODEL_for_Neckline_Classification.ipynb**  

Implements a CNN architecture for classifying necklines: 
- This CNN consists of 4 convolutional layers, each followed by max pooling.  
- Uses two fully connected layers with dropout for regularization.  
- The final dense layer outputs 3 class probabilities using softmax activation.  
  
![image](https://github.com/user-attachments/assets/39a6efdf-5b8a-40be-ac25-d804df7c83df)  


Results of this CNN Model:  

![Screenshot 2025-03-15 160859](https://github.com/user-attachments/assets/43be709d-5f5c-4f78-a3a8-6e5583975b5c)
![Screenshot 2025-03-15 160913](https://github.com/user-attachments/assets/109ffd3c-c78e-41dc-828a-ca5d55599921)  

Confusion Matrix of CNN Model:  

![image](https://github.com/user-attachments/assets/e0986f68-cdb2-4f35-ad7d-1c0d49eeea9c)  

1. Label 0: Round Neck  
2. Label 1: Scoop Neck  
3. Label 2: V-Neck Neck  

**Neckline_Classification_Models_with_Oversampling.ipynb**  
Applied SMOTE to address class imbalance and improve model performance.  
Implemented **VGG16**, **MobileNet**, and **ResNet50** for feature extraction and classification.  

VGG16 Confusion Matrix:  

![vgg16](https://github.com/user-attachments/assets/62f6f2eb-e299-4801-a04e-373334908d0e)  

MobileNet Confusion Matrix:  

![mobilenet](https://github.com/user-attachments/assets/fd8684ed-6096-41db-870a-27381bf83d0c)  

Resnet50 Confusion Matrix:  

![resnet50](https://github.com/user-attachments/assets/9e093458-0348-4cba-b8da-b0c060d193a6)  

**Neckline_Classifier_Model_Testing.ipynb**
Loads trained models and performs inference on test datasets.
Evaluates performance using precision, recall, and confusion matrices.
Includes visualizations of predictions.
