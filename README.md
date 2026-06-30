# MedLiteNeuro-AE
Efficient Feature Learning–Driven Neuroimage Compression and High-Fidelity Reconstruction using a Lightweight Autoencoder
# 🧠 MedLiteNeuro-AE
### Efficient Feature Learning–Driven Neuroimage Compression and High-Fidelity Reconstruction using a Lightweight Autoencoder

> 🚀 **Published in the International Journal of Computational Intelligence Systems (Springer Nature)**



---

## 📖 About

**MedLiteNeuro-AE** is a lightweight deep learning framework for efficient compression and high-fidelity reconstruction of **MRI** and **CT brain images**.

Traditional medical image compression techniques such as **JPEG** and **JPEG2000** often struggle to preserve subtle anatomical details that are essential for clinical diagnosis. MedLiteNeuro-AE addresses this challenge by learning adaptive latent representations through a lightweight encoder-decoder architecture inspired by **SegNet** and **UNet++**.

The proposed framework enables efficient storage, secure transmission, and scalable deployment of neuroimaging data while maintaining diagnostic image quality.

---

## 🌟 Highlights

- 🏆 Springer Journal Publication
- 🧠 Lightweight SegNet-inspired Autoencoder
- 📦 Efficient Medical Image Compression
- 🏥 Designed for MRI & CT Neuroimaging
- ☁️ Suitable for Cloud & Hospital Storage Systems
- ⚡ Lightweight Model (3.87 MB)
- 🔒 Implicit Security through Latent Representations

---

# 📄 Publication

**Efficient Feature Learning–Driven Neuroimage Compression and High-Fidelity Reconstruction using a Lightweight Autoencoder**

📚 **International Journal of Computational Intelligence Systems (Springer Nature)**

🔗 Paper: https://lnkd.in/gT2zcuQC

---

# 🎯 Motivation

Modern healthcare systems generate thousands of high-resolution MRI and CT scans daily. While these images are essential for diagnosis and treatment planning, they also create significant challenges in:

- Medical image storage
- Cloud transmission
- PACS repositories
- Telemedicine
- Remote diagnostics
- Healthcare infrastructure scalability

Traditional compression algorithms rely on handcrafted transformations and often sacrifice diagnostically important image details.

MedLiteNeuro-AE uses **deep feature learning** to compress neuroimages while preserving structural information required for clinical interpretation.

---

# 🏗 Model Architecture

```
                     MRI / CT Image
                            │
                            ▼
                    Image Preprocessing
             (Resize • Normalize • Augmentation)
                            │
                            ▼
                     Encoder Network
          (Depthwise Separable Convolutions)
                            │
                            ▼
                  Latent Feature Representation
                  (Compressed Image Encoding)
                            │
                            ▼
                     Decoder Network
              (High-Fidelity Reconstruction)
                            │
                            ▼
                 Reconstructed Medical Image
                            │
                            ▼
                  Image Quality Evaluation
```

---

# ⚙️ Workflow

```
Medical Image
      │
      ▼
Preprocessing
      │
      ▼
Encoder
      │
      ▼
Latent Representation
      │
      ▼
Decoder
      │
      ▼
Reconstructed Image
      │
      ▼
Performance Evaluation
```

---

# 🧠 Deep Learning Pipeline

### 1️⃣ Data Preparation

- MRI Brain Images
- CT Brain Images
- Image Normalization
- Resizing
- Train/Test Split

---

### 2️⃣ Encoder

The encoder extracts discriminative features while progressively compressing the image into a compact latent representation.

Key Components:

- Separable Convolution
- Batch Normalization
- ReLU Activation
- Max Pooling

---

### 3️⃣ Latent Representation

The encoder converts the original image into a compact feature space.

Advantages:

- Reduced storage requirements
- Faster transmission
- Lower computational cost
- Implicit privacy since latent features are not directly interpretable

---

### 4️⃣ Decoder

The decoder reconstructs the compressed image while preserving diagnostically important structures.

Key Components:

- Upsampling
- Skip Connections
- Separable Convolutions
- Batch Normalization

---

### 5️⃣ Performance Evaluation

Reconstructed images are evaluated against the original images using multiple objective quality metrics.

---

# 📊 Results

| Metric | Value |
|---------|-------|
| MSE | 0.000031 |
| RMSE | 0.005042 |
| PSNR | **46.54 dB** |
| SSIM | **99.66%** |
| MS-SSIM | **99.66%** |
| Compression Rate | **3.12%** |
| Model Size | **3.87 MB** |

---

# 🚀 Key Contributions

- Developed a lightweight deep learning framework for medical image compression.
- Designed an efficient encoder-decoder architecture inspired by SegNet and UNet++.
- Learned compact latent representations for MRI and CT images.
- Preserved diagnostic image quality after reconstruction.
- Reduced storage and transmission requirements for neuroimaging workflows.
- Demonstrated independent functionality of encoder and decoder as compressor and decompressor modules.
- Proposed a scalable solution for cloud-based and edge healthcare environments.

---

# 💻 Tech Stack

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

# 📈 Evaluation Metrics

The model is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)
- Multi-Scale Structural Similarity (MS-SSIM)

These metrics quantify reconstruction fidelity and structural preservation of medical images.

---

# 🌍 Applications

- Hospital PACS Systems
- Medical Image Archiving
- Telemedicine
- Cloud Healthcare Platforms
- Remote Diagnostics
- Healthcare Edge Devices
- Medical AI Infrastructure

---

# 🔬 Future Work

- Transformer-based Image Compression
- 3D MRI Volume Compression
- Federated Learning for Healthcare
- Explainable AI (Grad-CAM)
- Real-Time Edge Deployment
- Hybrid Lossless Compression

---

# 📂 Repository Structure

```
MedLiteNeuro-AE/
│
├── dataset/
│
├── notebooks/
│
├── models/
│   ├── encoder.py
│   ├── decoder.py
│   └── autoencoder.py
│
├── utils/
│
├── results/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

# 🎖 Research Impact

This work demonstrates that deep learning-based feature learning can efficiently compress medical neuroimages while preserving diagnostic fidelity.

The proposed framework supports practical deployment across healthcare environments by reducing storage requirements, improving transmission efficiency, and enabling scalable neuroimaging workflows.

---

# 👩‍💻 Authors

**Madayanthikaa Ramesh**  
Integrated M.Tech Computer Science & Engineering  
AI • Deep Learning • Computer Vision • Medical Imaging

---

## 📜 Citation

If you use this work in your research, please cite:

```bibtex
@article{MedLiteNeuroAE2026,
  title={Efficient Feature Learning--Driven Neuroimage Compression and High-Fidelity Reconstruction using a Lightweight Autoencoder},
  journal={International Journal of Computational Intelligence Systems},
  publisher={Springer Nature},
  year={2026}
}
```

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
