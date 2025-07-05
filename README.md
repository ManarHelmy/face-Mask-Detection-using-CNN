# 😷 Face Mask Detection using CNN

This project implements a **Convolutional Neural Network (CNN)** for detecting whether people in images are wearing face masks or not. The model is designed to be:
- Easily integrated into surveillance systems.
- Used for automated monitoring in public spaces.
- Extendable for deployment on edge devices like Raspberry Pi.

## 📂 Dataset
- **Classes:** `with_mask`, `without_mask`.
- Images resized to `128x128` for consistency.
- Uses **data augmentation** (rotation, zoom, shift, shear, flip) to improve generalization.

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- OpenCV (for real-time webcam detection)
- Matplotlib, Pandas, NumPy (for preprocessing and visualization)

## ⚙️ Model Architecture
- 3 Convolutional layers with ReLU activation.
- MaxPooling layers to reduce spatial dimensions.
- Dropout to prevent overfitting.
- Fully connected dense layer.
- Output with Sigmoid activation for binary classification.

## 📈 Results
✅ Achieved ~93% validation accuracy on the dataset.
✅ The model generalizes well on unseen data.
✅ Real-time webcam detection with bounding boxes and labels indicating **mask/no mask**.

