# Bean-leaf-disease-classification-using-Mobilenet-model
This project focuses on classifying bean leaf diseases using deep learning with MobileNet architectures (V1 & V2). The model identifies whether a bean leaf is healthy or affected by Angular Leaf Spot or Bean Rust, enabling early disease detection to improve crop yield and reduce losses.

A publicly available image dataset containing 1295 labeled bean leaf images was used. Images were preprocessed (resizing, scaling, shuffling, caching) and trained using TensorFlow and Keras. Transfer learning was applied with MobileNet models, followed by custom classification layers. Multiple optimizers were evaluated to compare performance.

The MobileNet V1 model achieved the best results, with over 98% training accuracy and 92% test accuracy, demonstrating high efficiency and suitability for lightweight and mobile-based agricultural applications.

Key Highlights:

Deep Learning–based image classification

MobileNet V1 & V2 (Transfer Learning)

TensorFlow & Keras implementation

3-class classification (Healthy, Angular Leaf Spot, Bean Rust)

High accuracy with low computational cost
