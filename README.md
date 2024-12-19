# Brain-Tumor-Classification-10-classes

# Brain Tumor Detection with Deep Learning

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies and Tools](#technologies-and-tools)
- [Dataset Details](#dataset-details)
- [Model Architecture](#model-architecture)
- [Front-End Functionality](#front-end-functionality)
- [Future Scope](#future-scope)
- [Installation and Usage](#installation-and-usage)
- [License](#license)

---

## Overview
This project leverages deep learning techniques to classify brain tumors into four categories: **glioma**, **meningioma**, **pituitary tumor**, and **no tumor**. The solution includes a user-friendly front-end interface, designed to make the tool accessible and efficient for medical professionals and researchers. The primary goal is to facilitate accurate and rapid brain tumor detection from MRI images.

---

## Features
1. **Deep Learning Model for Classification**:
   - Detects four classes of brain tumors:
     - *Glioma*: A tumor occurring in the brain and spinal cord.
     - *Meningioma*: A tumor on the membranes covering the brain and spinal cord.
     - *Pituitary Tumor*: A growth in the pituitary gland.
     - *No Tumor*: Indicates no tumor is present.

2. **User-Friendly Front-End Interface**:
   - Enables users to upload MRI images easily.
   - Displays predictions with detailed classification results.
   - Provides a seamless user experience for healthcare professionals.

3. **Dataset and Training**:
   - Dataset is organized into **training** and **testing** folders.
   - Images are pre-processed for improved accuracy and model robustness.

4. **Real-Time Prediction**:
   - Upload an MRI image in the supported format (e.g., JPEG, PNG).
   - Get instant classification results.

---

## Technologies and Tools
1. **Deep Learning Frameworks**:
   - TensorFlow/Keras for model development.
   - OpenCV for image processing and pre-processing.

2. **Front-End**:
   - Streamlit or React.js for a user-friendly interface.
   - Displays results and handles user interactions.

3. **Backend**:
   - Python-based backend with Flask or Django for handling predictions.

4. **Other Tools**:
   - NumPy and Pandas for data manipulation.
   - Matplotlib and Seaborn for visualizations and insights.

---

## Dataset Details
- The dataset consists of MRI images, categorized into the following four classes:
  - `glioma`
  - `meningioma`
  - `pituitary`
  - `no tumor`

- **Training and Testing Split**:
  - Training set: Contains labeled images for model training.
  - Testing set: Used to evaluate the model's performance.

- **Pre-processing Steps**:
  - Resizing images to a uniform size (e.g., 224x224 pixels).
  - Normalizing pixel values for better model training.

---

## Model Architecture
1. **Base Architecture**:
   - A Convolutional Neural Network (CNN) model.
   - Includes convolution, pooling, and dense layers.

2. **Additional Techniques**:
   - Data augmentation (e.g., rotation, flipping) to increase dataset diversity.
   - Early stopping and learning rate scheduling to optimize training.

3. **Performance Metrics**:
   - Accuracy, precision, recall, and F1-score used to evaluate the model.

---

## Front-End Functionality
- A simple interface that allows users to:
  - Upload an MRI image.
  - View classification results in real time.
  - Access additional resources or insights from predictions.

---

## Future Scope
1. **Brain Tumor Segmentation**:
   - Incorporate segmentation techniques to pinpoint tumor regions in the MRI.

2. **Explainability**:
   - Use methods like Grad-CAM to provide visual explanations of the model’s predictions.

3. **Larger Dataset**:
   - Enhance the model's performance by training on a larger and more diverse dataset.

4. **Mobile Accessibility**:
   - Extend the application to mobile devices for on-the-go predictions.

5. **Integration with Medical Pipelines**:
   - Collaborate with medical professionals to integrate the tool into diagnostic workflows.

---

## Installation and Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/brain-tumor-detection.git
   cd brain-tumor-detection
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   Launch the application (backend and front-end):
   ```bash
   python app.py
   ```

4. **Access the Interface**:
   Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

5. **Upload and Predict**:
   - Upload an MRI image.
   - View the classification result in real time.

---

## License
This project is licensed under the [MIT License](LICENSE).

