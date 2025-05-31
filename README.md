📌 Overview
This project builds a Convolutional Neural Network (CNN) from scratch to classify images in the CIFAR-10 dataset. It focuses on enhancing performance, improving generalization, and interpreting the training process through essential techniques such as data augmentation, regularization, and learning rate scheduling.

🎯 Objectives
Classify images into 10 CIFAR-10 categories with high accuracy.

Visualize model performance and training behavior through learning curves and confusion matrix.

Implement the entire process using the PyTorch library.

⚙️ Tools & Techniques
Language: Python

Framework: PyTorch


🧠 Optimization Strategies
Data Augmentation: RandomCrop, RandomHorizontalFlip, RandomErasing

Regularization: Dropout (0.5), Weight Decay (5e-4), Label Smoothing (0.1)

Optimizer: AdamW

Learning Rate Scheduler: ReduceLROnPlateau (mode='min', factor=0.1, patience=3, min_lr=1e-6)

Early Stopping: Patience = 5

📈 Results
Test Accuracy: 86.20%

Best Validation Loss: 0.9104 (at epoch 56)

Epochs Run: 61

🔍 Highlights
Hierarchical feature extraction using a CNN architecture with progressively increasing channel depth (from 3 to 128) and decreasing spatial resolution, effectively capturing both low-level and high-level visual patterns.

Robust generalization enabled by extensive data augmentation and regularization techniques, helping the model avoid overfitting despite the relatively small dataset size.

Label smoothing contributed to more calibrated predictions by reducing overconfidence in the model’s outputs, leading to better generalization.

Class confusion between cats and dogs remains a challenge, highlighting typical CNN limitations when dealing with low-resolution and visually similar categories. Vehicle classes (car, ship, truck) showed exceptionally high accuracy.


👤 Author
Phùng Thu Hương
📧 Email: thuhuong22062005@gmail.com
🌐 GitHub: github.com/Kaohtp

📝 This project is an assignment for the Python course. All models and results are achieved through thorough experimentation and careful optimization.
