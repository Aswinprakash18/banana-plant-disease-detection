
# LeNet-Based Banana Plant Disease Detection  

## Overview  
This project implements a **LeNet-5 deep learning model** for detecting **banana plant diseases** using leaf images. LeNet-5, a **lightweight Convolutional Neural Network (CNN)**, is optimized for **low-complexity image classification tasks**, making it suitable for real-time disease detection in agriculture.  

## Features  
✅ **Automated Disease Detection** – Identifies common banana plant diseases.  
✅ **Lightweight Architecture** – Efficient for mobile and edge devices.  
✅ **Preprocessing & Augmentation** – Improves model robustness.  
✅ **High Accuracy** – Reliable classification results.  
✅ **Deployment Ready** – Can be integrated into mobile apps or IoT devices.  

## Dataset  
The model is trained on a dataset containing images of banana leaves classified into:  
- **Healthy Leaves**  
- **Diseased Leaves** (e.g., Black Sigatoka, Fusarium Wilt, Banana Bunchy Top Virus)  

## Workflow  
### **1. Data Preprocessing**  
- Load and preprocess banana leaf images.  
- Resize images to **32x32 pixels** (LeNet-5 input size).  
- Apply **normalization and augmentation** (rotation, flipping).  

### **2. Model Architecture (LeNet-5)**  
LeNet-5 consists of:  
- **Two Convolutional Layers** for feature extraction.  
- **Two Subsampling (Pooling) Layers** for dimensionality reduction.  
- **Fully Connected Layers** for classification.  
- **Softmax Activation** for disease category prediction.  

### **3. Model Training**  
- Train using **categorical cross-entropy loss** and **Adam optimizer**.  
- Validate on a test dataset to ensure generalization.  

### **4. Prediction & Deployment**  
- Classifies input leaf images as **healthy or diseased**.  
- Provides **confidence scores** for each prediction.  
- Can be deployed on **mobile apps, web platforms, and IoT devices**.  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/lenet-banana-disease-detection.git
   cd lenet-banana-disease-detection

   Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Train the model:
bash
Copy
Edit
python train.py
Run inference on a sample image:
bash
Copy
Edit
python predict.py --image sample_leaf.jpg
Results
Achieved high accuracy in detecting banana plant diseases.
Low computational cost, making it ideal for mobile and IoT-based applications.
Future Improvements
🔹 Increase dataset size for better generalization.
🔹 Optimize for edge computing with TensorFlow Lite.
🔹 Implement real-time disease detection in mobile apps.

License
This project is licensed under the MIT License.

Contributors
🚀  Developer & Researcher -aswinpraksh and sivasreeram

