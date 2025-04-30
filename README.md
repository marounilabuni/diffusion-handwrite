
# 🌀 Diffusion-Based Character Image Generator

> A PyTorch-based implementation of a **Denoising Diffusion Probabilistic Model (DDPM)** trained on the EMNIST dataset to generate handwritten characters from noise.

![PyTorch](https://img.shields.io/badge/framework-PyTorch-red?logo=pytorch&logoColor=white)
![License](https://img.shields.io/badge/license-Apache%202.0-blue)
![Status](https://img.shields.io/badge/status-Active-green)

---

## 📦 Dataset
We use the [EMNIST](https://www.nist.gov/itl/products-and-services/emnist-dataset) dataset to train a character generation model. It includes thousands of grayscale handwritten character images.

```python
from torchvision.datasets import EMNIST
```

---


## 🚀 How to Run

1. Clone the repo and navigate to the notebook:

```bash
git clone https://github.com/marounilabuni/diffusion-handwrite.git
cd diffusion-handwrite
```

2. Install dependencies:

```bash
pip install torch torchvision matplotlib tqdm
```

3. Open the notebook:

```bash
jupyter notebook diffusion_images_final.ipynb
```

---

## 🧪 Sampling Preview

Once trained, the model can generate samples like these:

> _[Insert sample images or grid here, e.g., using `make_grid()`]_  
> `make_grid()` is used to visualize multiple character generations at once.

---

## 📁 Project Structure

```
├── diffusion_images_final.ipynb   # Main training & sampling
└── README.md                      # Project overview
```

---

## 🧠 Future Work

- ✅ Add DDIM sampling
- 🔄 Add case-sensitive character generation (upper vs lower)
- 🧬 Enable style-conditioned character generation to mimic specific handwriting

---

## 📄 License
This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

---

> Crafted with 💻 + ☕ by Maroun Ilabuni.
