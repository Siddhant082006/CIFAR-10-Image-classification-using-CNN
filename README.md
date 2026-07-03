# CIFAR-10-Image-classification-using-CNN

A custom PyTorch Convolutional Neural Network (CNN) built to classify the CIFAR-10 dataset into 10 categories.
Key Details:
•	Architecture: Custom CNN (1.1M parameters) with 2 Convolutional blocks, Batch Normalization, and Dropout.
•	Training: Trained for 30 epochs using the Adam optimizer, a Cosine Annealing learning rate scheduler, and robust data augmentation (RandomCrop, HorizontalFlip, ColorJitter).
•	Results: Achieved 77.83% accuracy and a 0.6305 loss on the test set.
•	Tech Stack: PyTorch, Torchvision, NumPy, Matplotlib, Scikit-learn.
Usage:
Ensure you have the required libraries installed and run the cells sequentially in the provided Jupyter/Colab notebook. The script will automatically download the dataset, train the model, plot the learning curves
