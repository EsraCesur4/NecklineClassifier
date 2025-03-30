# 👗 Neckline Classifier

The primary goal of this project is to classify different types of necklines in fashion images using deep learning models. The project includes:  

## **CNN_MODEL_for_Neckline_Classification.ipynb**  

Implements a CNN architecture for classifying necklines: 
🔹 This CNN consists of 4 convolutional layers, each followed by max pooling.  
🔹 Uses two fully connected layers with dropout for regularization.  
🔹 The final dense layer outputs 3 class probabilities using softmax activation.  
  
![image](https://github.com/user-attachments/assets/39a6efdf-5b8a-40be-ac25-d804df7c83df)  


## 📊 CNN Model Results

![Screenshot 2025-03-15 160859](https://github.com/user-attachments/assets/43be709d-5f5c-4f78-a3a8-6e5583975b5c)
![Screenshot 2025-03-15 160913](https://github.com/user-attachments/assets/109ffd3c-c78e-41dc-828a-ca5d55599921)  
![image](https://github.com/user-attachments/assets/30ad4bcc-bbda-4af0-95d2-094183ca3ad4)


## 🧮 Confusion Matrix of CNN Model:  

![image](https://github.com/user-attachments/assets/e0986f68-cdb2-4f35-ad7d-1c0d49eeea9c)  

1. Label 0: Round Neck  
2. Label 1: Scoop Neck  
3. Label 2: V-Neck Neck  

## **Neckline_Classification_Models_with_Oversampling.ipynb**  
Applied SMOTE to address class imbalance and improve model performance.  
Implemented **VGG16**, **MobileNet**, and **ResNet50** for feature extraction and classification.  

## 📈 Model Performances
VGG16 Confusion Matrix:  

![image](https://github.com/user-attachments/assets/84a77ada-6a59-4032-9ec4-b957fbaa18e9)
![vgg16](https://github.com/user-attachments/assets/62f6f2eb-e299-4801-a04e-373334908d0e)  

MobileNet Confusion Matrix:  

![image](https://github.com/user-attachments/assets/2465c7ac-6061-4b99-a68d-69ce8fec3553)
![mobilenet](https://github.com/user-attachments/assets/fd8684ed-6096-41db-870a-27381bf83d0c)  

Resnet50 Confusion Matrix:  

![image](https://github.com/user-attachments/assets/3f841481-09a7-4954-996d-62df84fde539)
![resnet50](https://github.com/user-attachments/assets/9e093458-0348-4cba-b8da-b0c060d193a6)  

## 🛠️ Used Technologies

### 🧪 Frameworks & Libraries
- **TensorFlow** – Deep learning framework for model building and training  
- **Keras** – High-level API for designing neural networks  
- **OpenCV** – Image preprocessing and manipulation  
- **Matplotlib / Seaborn** – For visualizing data and results  
- **Scikit-learn** – Confusion matrix, metrics, and SMOTE oversampling  
- **NumPy / Pandas** – Data manipulation and numerical operations  

### 📚 Models Used
-  Custom CNN (built from scratch)  
-  VGG16 (pretrained)  
-  MobileNet (pretrained)  
-  ResNet50 (pretrained)  

### ⚙️ Techniques
-  **SMOTE** – Synthetic Minority Oversampling Technique for class imbalance  
-  **Transfer Learning** – Using pretrained models as feature extractors  
-  **Image Normalization & Resizing** – For consistent model input  
-  **Softmax Activation** – For multi-class classification  
