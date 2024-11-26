# Lab 2

## Objective
This lab involves building and comparing various deep learning models (CNN, Faster R-CNN, and Vision Transformer) for image classification tasks on the MNIST dataset using PyTorch. The main objectives of the lab project are:

### Part 1: CNN Classifier
- Build a CNN model to classify images from the MNIST dataset.
- Implement Faster R-CNN to perform the same classification task.
- Compare the two models using performance metrics like Accuracy, F1 score, Loss, and Training time.
- Fine-tune pretrained models like VGG16 and AlexNet on the MNIST dataset and compare their results with the CNN and Faster R-CNN models.

### Part 2: Vision Transformer (ViT)
- Implement a Vision Transformer (ViT) model from scratch for image classification on the MNIST dataset.
- Interpret the results obtained and compare them with the CNN and Faster R-CNN models.

## Key Takeaways
This lab provided valuable hands-on experience with different deep learning models, including CNNs, Faster R-CNNs, and Vision Transformers (ViTs). I learned that **CNNs** are effective for image classification tasks, achieving good accuracy with relatively low training time. **Faster R-CNNs**, while slower, excel in object detection tasks due to their region proposal networks. Fine-tuning pretrained models like **VGG16 and AlexNet** on MNIST led to slight improvements in accuracy over the CNN model. **Vision Transformers**, though computationally expensive, showed competitive performance and highlighted the potential of transformer-based architectures for vision tasks. Overall, CNNs remain efficient for simple tasks like MNIST, while ViTs hold promise for larger and more complex datasets.
