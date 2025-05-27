# Module 13: Image Classification – Intel Dataset using PyTorch

### Assignment Summary
This assignment focused on applying deep learning with **PyTorch** for image classification using the **Intel Image Classification dataset** from Kaggle. The task involved feature extraction with **OpenCV**, image preprocessing, neural network model development, and performance evaluation.

### Tasks Covered
- Downloaded and extracted the **Intel Image Classification dataset**, containing six classes:
  - `buildings`, `forest`, `glacier`, `mountain`, `sea`, `street`
- Loaded training and testing images using **OpenCV (cv2)**:
  - Resized each image to `(128, 128)`
  - Converted color channels (noted as BGR by default in OpenCV)
  - Mapped each image to its respective label index
- Converted image lists into **NumPy arrays** with shape `(14034, 128, 128, 3)`
- Scaled pixel values to the `[0, 1]` range to normalize the input data
- Built a **fully connected neural network** in PyTorch:
  - Flattened the 3D input to a 1D vector before feeding into the network
  - Used 3 hidden layers with 50 neurons each
  - Trained over multiple epochs (~200)
  - Achieved >60% accuracy on training and ~55% on testing with minimal tuning
- Outlined ideas to further improve the model, such as:
  - Using **Convolutional Neural Networks (CNNs)** instead of fully connected layers
  - Incorporating **data augmentation** and **batch normalization**
  - Experimenting with **learning rate scheduling** and **dropout layers**

### Highlights
- Demonstrated how raw image data can be processed and classified using PyTorch and OpenCV.
- Explored limitations of MLPs for image data and outlined paths for improvement using CNNs.
- Reinforced the need for tensor reshaping and memory-efficient processing in image classification tasks.

### File
- `Shewale_Assign13.ipynb`: Complete image classification pipeline including image loading, preprocessing, neural network training, performance evaluation, and improvement suggestions.
