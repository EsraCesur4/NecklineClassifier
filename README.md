# NecklineClassifier

The primary goal of this project is to classify different types of necklines in fashion images using deep learning models. The project includes:  

Files in This Repository
**CNN_MODEL_for_Neckline_Classification.ipynb**  

Implements a CNN architecture for classifying necklines: 
- This CNN consists of 4 convolutional layers, each followed by max pooling.  
- Uses two fully connected layers with dropout for regularization.  
- The final dense layer outputs 3 class probabilities using softmax activation.
  
![image](https://github.com/user-attachments/assets/39a6efdf-5b8a-40be-ac25-d804df7c83df)

Results of this CNN Model:


**Neckline_Classification_Models_with_Oversampling.ipynb**
Implements oversampling techniques (e.g., SMOTE) to handle class imbalance.
Evaluates the effect of oversampling on model performance.
Includes model comparison based on accuracy and F1-score.

**Neckline_Classifier_Model_Testing.ipynb**
Loads trained models and performs inference on test datasets.
Evaluates performance using precision, recall, and confusion matrices.
Includes visualizations of predictions.
