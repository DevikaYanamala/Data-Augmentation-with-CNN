# Data-Augmentation-with-CNN
# 🌸 Data Augmentation with CNNs (Flower Dataset)

This project demonstrates **image data augmentation** techniques using **TensorFlow/Keras** on the **Flower dataset**.  
Data augmentation helps improve model generalization by artificially expanding the training dataset with transformed images.

---

## 📊 Dataset Overview
- Dataset: **TensorFlow Flowers**  
- Classes: `daisy`, `roses`, `tulips`, `sunflowers`, `dandelion`  
- Total images: ~3,670  
- Source: [TensorFlow dataset](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)  

---

## ⚙️ Features of the Notebook
- Load dataset using `tf.keras.utils.get_file`  
- Preprocess images with `image_dataset_from_directory`  
- Visualize original dataset samples  
- Apply **data augmentation** with:
  - Random flips  
  - Random rotations  
  - Random zoom  
  - Random contrast  
- Build a **CNN model** using `Sequential` and `Conv2D` layers  
- Train the CNN on augmented data  
- Evaluate performance on test set  

---

## 🚀 Tech Stack
- **Python 3**  
- **TensorFlow/Keras** → deep learning & augmentation  
- **NumPy** → numerical computations  
- **matplotlib** → visualization  
- **OpenCV** → image processing  
- **Pillow (PIL)** → image handling
  
---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DevikaYanamala/Data-Augmentation-with-CNN.git
   cd Data-Augmentation-with-CNN
   
   pip install -r requirements.txt
   jupyter notebook Data_Agumentatiom.ipynb
