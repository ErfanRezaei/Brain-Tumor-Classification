# Brain Tumor Classification using CNN and Vision Transformer (ViT)

This project explores the classification of brain tumors from MRI images into four categories: glioma, meningioma, no tumor, and pituitary. Two distinct deep learning architectures are implemented and compared: a classic **Convolutional Neural Network (CNN)** and a modern **Vision Transformer (ViT)**.

---

### Models Implemented

1.  **Convolutional Neural Network (CNN):** A foundational deep learning architecture for image classification, effective at learning spatial hierarchies of features from images.
2.  **Vision Transformer (ViT):** A modern architecture that applies the transformer model, originally designed for NLP, to image classification tasks by treating images as sequences of patches.

---

### Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib / Seaborn

---

### How to Run This Project

**1. Clone the Repository:**
First, clone the project from GitHub:
```bash
git clone [https://github.com/ErfanRezaei/Brain-Tumor-Classification.git](https://github.com/ErfanRezaei/Brain-Tumor-Classification.git)
cd Brain-Tumor-Classification
```
**2. Install Dependencies:**
```bash
pip install -r requirements.txt
```
Note: It's highly recommended to use a virtual environment to keep project dependencies isolated.

**3. Download the Dataset:**

Download the dataset from [Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri). From the downloaded files, place the Training/ and Testing/ folders into the root of the project directory.

**4: Run the Notebooks:**

This project contains two separate notebooks, one for each model. You can run them independently:

- `Brain Tumor Classification (CNN).ipynb`
- `Brain Tumor Classification (ViT).ipynb`

Launch Jupyter Notebook and open the desired file to start training and evaluation.
