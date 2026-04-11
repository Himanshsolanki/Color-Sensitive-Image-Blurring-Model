# 🧠 Image Blurring using Convolution (PyTorch)

This project demonstrates how to perform **image blurring using convolution** in **PyTorch**, starting from raw image loading to applying a custom kernel and visualizing the result.

---

## 🚀 Overview

- Load an image using PIL  
- Convert it into a tensor  
- Apply a **custom blur kernel (5×5)**  
- Perform convolution using `torch.nn.functional.conv2d`  
- Visualize the processed image  

---

## 🧠 Key Concept

This project is based on:

👉 **Convolution Operation in Deep Learning / Computer Vision**

A blur effect is achieved by averaging pixel values using a kernel.

---

## ⚙️ Workflow

### 1️⃣ Install Dependencies

```bash
pip install torch torchvision pillow matplotlib numpy
