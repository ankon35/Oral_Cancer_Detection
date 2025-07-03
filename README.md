# 🧠 Oral Cancer Detection using Vision Transformer (ViT)

This project leverages **Vision Transformer (ViT)** models to detect oral cancer using a **merged dataset** of clinical and histopathological images. By combining two different types of data sources, we aim to create a more diverse and robust model for accurate cancer classification.

---

## 📁 Dataset Description

We used two distinct datasets:

- **Clinical Dataset**: Includes visual clinical features of oral lesions.
- **Histopathological Dataset**: Comprises microscopic images of tissue samples.

These datasets were merged to create a **diverse and balanced training set**. Preprocessing steps included:

- Data merging and labeling
- Image resizing and normalization
- Dataset shuffling and splitting (train/val/test)

---

## 🧠 Model Architecture

We used a **Vision Transformer (ViT)** architecture, which treats image patches similarly to tokens in NLP transformers. The model is trained from scratch (or fine-tuned from a pre-trained ViT model) on the combined dataset.

---

## 📊 Results

### ✅ Performance Metrics

- **Highest Validation Accuracy**: `99.92%`
- **Highest Test Accuracy**: `99.22%`


---

## 📉 Confusion Matrix

![Confusion Matrix](/confusion%20matrix.png)

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this software, provided that you include proper attribution to the original author.

See the full license in the [LICENSE](./LICENSE) file.


