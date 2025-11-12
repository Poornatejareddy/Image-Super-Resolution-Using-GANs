# 🧠 Image Super-Resolution Using GANs (SRGAN)

This repository contains a **Google Colab / Jupyter Notebook** implementation of **Super-Resolution GAN (SRGAN)** — a deep learning model that enhances low-resolution images into high-resolution outputs.

---

## 📘 Overview

- The notebook implements the **full SRGAN pipeline**: data loading, model definition, training, and inference.
- Trained on the **DIV2K dataset**.
- Generates **4× super-resolved** images.
- Works directly in **Google Colab** or any **Jupyter environment** — no manual scripts required.

---

## 🚀 How to Run the Notebook

### Option 1 — 💻 Run in Google Colab
1. Open the notebook directly in Colab:
```

https://colab.research.google.com/drive/1GpTzqtAhCMQVS7QBHFGw_2YMPdn1rcTo?usp=sharing
````
2. Click **“Runtime” → “Change runtime type” → Select GPU**.
3. Run all cells sequentially (from top to bottom).

---

### Option 2 — 🧠 Run Locally (Jupyter)
1. Clone the repo and install dependencies:
```bash
git clone https://github.com/Poornatejareddy/Image-Super-Resolution-Using-GANs.git
cd <repo-name>
pip install torch torchvision pillow tqdm matplotlib
jupyter notebook
````

2. Open `image_sr_gan_final.ipynb` in Jupyter.
3. Run all cells to train or test the model.

---

## 🧾 Notebook Sections

| Section              | Description                                        |
| -------------------- | -------------------------------------------------- |
| **Setup & Imports**  | Installs dependencies and configures environment   |
| **Dataset Loader**   | Downloads and preprocesses DIV2K images            |
| **Model Definition** | Builds SRGAN generator and discriminator           |
| **Training Loop**    | Trains the SRGAN with content and adversarial loss |
| **Inference**        | Upscales a test image using trained weights        |
| **Visualization**    | Shows comparison of LR vs SR images                |

---

## 📊 Output

After running training or inference, you’ll get:

* Generated super-resolution images (`SRGAN_result.png`)
* Saved model weights (`G_epochX.pth`)

---

## 🧰 Requirements

```
torch
torchvision
pillow
tqdm
matplotlib
```

All dependencies are automatically installed when you run the first cell in Colab.

---

## 📜 Reference

**Ledig et al., 2017 — Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network (CVPR)**

---

## 🏁 Quick Start (Colab Shortcut)

You can open and run the notebook instantly in Colab by clicking the badge below:

[![Open in Colab](https://colab.research.google.com/drive/1GpTzqtAhCMQVS7QBHFGw_2YMPdn1rcTo?usp=sharing)

```


