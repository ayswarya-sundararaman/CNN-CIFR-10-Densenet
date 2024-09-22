

# DenseNet CIFAR-10 Classification

This project uses the **DenseNet architecture** to classify images from the CIFAR-10 dataset. The model is built using convolutional layers and trained with data augmentation techniques to improve accuracy.

## Dataset
- **Dataset**: CIFAR-10 (60,000 32x32 color images in 10 classes).
- **Classes**: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck.

## Model Architecture
- **DenseNet**: Deep CNN model with densely connected convolutional layers.
- **Blocks**: Dense blocks, transition blocks, and output layer using softmax activation.
- **Hyperparameters**: 
  - Filters: 12
  - Dropout rate: 0.2
  - Batch size: 128
  - Epochs: 20
  - Optimizer: Adam

## Key Features
- **Data Augmentation**: Applied rotation, zoom, shear, and horizontal flip to enhance training.
- **Checkpointing**: Model weights saved at the best validation accuracy during training.
- **Batch Normalization**: Used to stabilize and accelerate convergence.
- **Pooling**: Average pooling applied between dense blocks.

## Results
- **Accuracy**: Achieved 78.4% accuracy on test data after 20 epochs.
- **Test Loss**: 0.6417

## Conclusion
DenseNet with data augmentation improves classification accuracy on the CIFAR-10 dataset, and the architecture effectively reduces overfitting while maintaining performance.

