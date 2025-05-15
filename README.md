# EyeDiseaseClassification
A deep learning project for classifying various retinal diseases from fundus images using Convolutional Neural Networks (CNNs). This project employs image augmentation techniques and a custom CNN architecture optimized with the Adam optimizer and valid padding. The goal is to support early diagnosis by accurately identifying different retinal conditions.

## 📌 Features
- Multi-class classification of retinal diseases from eye images
- Data augmentation techniques to improve model generalization
- Custom CNN architecture built with Keras and TensorFlow
- Performance evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Visualization of model training progress and confusion matrix using Matplotlib and Seaborn

## ⚙️ Tech Stack
- Python 3.7
- TensorFlow & Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Project Structure
- `Dataset/` – Dataset folder with images sorted by disease classes
- `SelectedImages/` - Consists of folders each representative of classes ( ODC, DR, MH, Normal)
- `model/` – Saved model weights and checkpoints
- `testImages` - Contains images that will test the performance of model
- `requirements.txt` - List of modules required
- `EyeDeepNet.ipynb` - Jupyter Notebook with full workflow (data preprocessing, model building, training, evaluation)

## 🛠️ Architecture
![image](https://github.com/user-attachments/assets/d2dd09ee-5c02-42c1-a03c-9374413d6b5b)


## 📊 Sample Visualizations
### Confusion Matrix
<img width="381" alt="image" src="https://github.com/user-attachments/assets/a90d5c12-41cb-4adb-93f0-366f02c9c327" />

### Confusion Matrix
<img width="404" alt="image" src="https://github.com/user-attachments/assets/c6adf045-5a2b-4c77-b233-63353521265d" />

### Confusion Matrix
![image](https://github.com/user-attachments/assets/5727dd8d-f3db-44f7-a4c9-1c46952f9645)


### Training Accuracy and Loss Curves


(Replace above images with your actual project screenshots)

## 🚀 Getting Started
- Clone the repository rflow numpy pandas matplotlib seaborn scikit-learn
- Run the notebook:
    - Execute step-by-step cells for data preprocessing and augmentation
- Train the CNN model on the dataset
- Evaluate the model’s performance with metrics and confusion matrix visualization


