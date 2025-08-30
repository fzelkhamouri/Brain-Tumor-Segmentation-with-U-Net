# 🧠 Brain Tumor Segmentation with U-Net

## 📌 Project Overview
This project applies **deep learning for medical image segmentation** using the **U-Net architecture**.  
It demonstrates how MRI brain images can be processed to **detect and segment tumor regions**.  

The work is inspired by my **PhD research** in medical imaging and showcases practical application of **convolutional neural networks** in healthcare.

---

## ⚙️ Tools & Libraries
- Python  
- TensorFlow / Keras  
- NumPy, OpenCV  
- Matplotlib, Seaborn  

---

## 🔑 Methodology
1. Load MRI dataset (BraTS or synthetic sample).  
2. Preprocess images (resize, normalize, grayscale).  
3. Build U-Net architecture.  
4. Train model with binary tumor masks.  
5. Evaluate segmentation performance (Dice coefficient, IoU).  
6. Visualize predictions vs ground truth.  

---

## 📊 Results
- U-Net successfully segments tumor areas on MRI scans.  
- Dice coefficient > 0.85 on validation set (using small dataset).  


---

## 🚀 Future Work
- Extend to **3D U-Net** for volumetric MRI scans.  
- Add transfer learning to improve accuracy.  
- Apply to real hospital datasets with anonymized scans.  

---

## 📂 Project Structure
