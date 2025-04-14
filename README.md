# Food-Detection-101
This project implements and compares two popular convolutional neural network (CNN) architectures — GoogLeNet (Inception v1) and MobileNetV2 — on the Food-101 dataset. The aim is to classify 101 different types of food images using deep learning techniques.

📂 Dataset : https://www.kaggle.com/datasets/dansbecker/food-101
The Food-101 dataset consists of:

101 food categories (1000 images from each category)

You can download the dataset from the official website or use torchvision.datasets.Food101 if you're using PyTorch.

🧠 Models Implemented:

🔍 GoogLeNet (Inception v1)
Deep CNN architecture introduced by Google.

Uses inception modules for computational efficiency.

Suitable for higher accuracy on large datasets.

📱 MobileNetV2
Lightweight CNN architecture by Google.

 📌Key Learnings
The trade-off between accuracy and model size/speed.

Data preprocessing and augmentation can significantly influence performance.

Transfer learning with pretrained models can boost results with fewer resources.

Designed for mobile and embedded vision applications.

Depthwise separable convolutions reduce computation and model size.

💡 Future Work
Implement more architectures like ResNet or EfficientNet.

Fine-tune hyperparameters for better accuracy.

Deploy as a web or mobile app for real-time food recognition.
