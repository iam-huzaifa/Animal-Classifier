#  Cat vs Dog Image Classifier

This project is part of my deep learning learning journey. The goal is to classify images of cats and dogs using three different approaches and understand how model performance improves with more advanced techniques.

## 📚 Project Overview

In this project, I implemented and compared three approaches for image classification:

1. **Simple CNN Classifier**
   - Built a Convolutional Neural Network (CNN) from scratch.
   - Trained the model on the Cats vs Dogs dataset.
   - Learned the fundamentals of convolutional layers, pooling, and image classification.

2. **Transfer Learning**
   - Used a pre-trained model as a feature extractor.
   - Kept the pre-trained layers frozen.
   - Trained only the classification head on the Cats vs Dogs dataset.
   - Achieved better performance with less training time.

3. **Fine-Tuning**
   - Started from the transfer learning model.
   - Unfroze selected layers of the pre-trained model.
   - Fine-tuned the network on the dataset with a low learning rate.
   - Improved the model's accuracy by adapting the pre-trained features to the new task.

## 🚀 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google colab


## 🎯 Learning Objectives

Through this project, I learned:

- Building CNNs from scratch
- Image preprocessing and data augmentation
- Transfer learning using pre-trained models
- Fine-tuning deep learning models
- Comparing different training strategies

## 🔮 Future Improvements

- Experiment with different pre-trained architectures (EfficientNet, ResNet, MobileNet, etc.)
- Deploy the model as a web application
