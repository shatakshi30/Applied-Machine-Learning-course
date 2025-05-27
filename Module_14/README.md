# Module 14: Convolutional Neural Networks – Intel Image Classification

### Assignment Summary
In this final module, the goal was to enhance image classification performance on the **Intel Image Classification dataset** using **Convolutional Neural Networks (CNNs)**. Compared to the fully connected model from Module 13, CNNs are more suited for handling spatial hierarchies and local patterns in image data.

### Tasks Covered
- Reused the Intel dataset, including training and test splits with six image classes:
  - `buildings`, `forest`, `glacier`, `mountain`, `sea`, `street`
- Loaded and resized images using **OpenCV**, maintaining shape `(128, 128, 3)`
- Normalized image pixel values to `[0, 1]`
- Converted NumPy arrays to PyTorch tensors and reshaped them appropriately
- Constructed a **CNN architecture** with the following structure:
  - Three convolutional layers with ReLU activation
  - MaxPooling after each conv layer
  - Flattened output followed by a fully connected layer
- Trained the CNN using **Adam optimizer** and **CrossEntropyLoss**
- Ran training for ~50 epochs, monitoring loss and accuracy on both training and test sets
- Achieved improved accuracy (~65% test accuracy) compared to previous MLP-based model

### Highlights
- The CNN outperformed the earlier MLP due to its ability to capture spatial features and local textures
- Demonstrated that deeper architectures with proper pooling and activation layers improve generalization
- Suggested possible further enhancements:
  - Add dropout or batch normalization
  - Introduce learning rate scheduling
  - Use data augmentation (e.g., flipping, rotation) for regularization

### File
- `Shewale_Assign14.ipynb`: Final deep learning notebook with CNN implementation, image preprocessing, training loop, accuracy reporting, and improvement recommendations.
- `module14_cnn_notebook.html`: Rendered HTML version for easy sharing or grading.
