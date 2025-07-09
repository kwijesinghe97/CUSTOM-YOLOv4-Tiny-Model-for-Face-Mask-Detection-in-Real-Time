# 😷 Real-Time Face Mask Detection with YOLOv4-Tiny

This project demonstrates a custom-trained **YOLOv4-tiny** object detector that identifies whether individuals are wearing face masks in real time. It's optimized for lightweight performance and suitable for real-time applications on low-resource systems.

---

## 📁 Repository Contents

The `yolov4-tiny` folder contains:
- `yolov4-tiny-custom.cfg` – Custom configuration file (for 2 classes)
- `obj.data` – Dataset metadata
- `obj.names` – Class labels (`with_mask`, `without_mask`)
- `process.py` – Script to generate `train.txt` and `test.txt` for training

> ⚠️ **Note**: The dataset (`obj.zip`) is not included here. Download it using the link below.

---

## 📦 Dataset Download

**Kaggle:**  
🔗 [Labeled Mask Dataset (YOLO Format)](https://www.kaggle.com/techzizou/labeled-mask-dataset-yolo-darknet)

- **Total Images:** 1510  
  - ~1350 manually labeled  
  - ~150 from Roboflow
- **Image Type:** Mostly close-up (~1300), with a few long-shot (~200)

You can also expand this dataset by adding your own images and labels. More sources are listed in the Medium article below.

---

## ⚙️ Model Overview

- **Framework:** Darknet  
- **Architecture:** YOLOv4-tiny  
- **Classes:**  
  - `with_mask`  
  - `without_mask`  
- Designed for **speed** and **real-time inference**

---

## 🚀 Try It Yourself

- 📔 [Google Colab Notebook](https://colab.research.google.com/drive/1hQO4nOoD6RDxdbz3C1YSiifTsyZjZpYm?usp=sharing)  
- 📝 [Medium Article](https://medium.com/@techzizou007/training-a-custom-detector-for-mask-detection-using-yolov4-tiny-darknet-b58be08c9593)  
- 🎥 [YouTube Tutorial](https://youtu.be/H3SJcwttTi4)

---

## 🙌 Credits

**Dataset Sources:**
- Prajnasb (GitHub)  
- Roboflow (by Joseph Nelson)  
- x-zhangyang (GitHub)

---
