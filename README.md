# 🧠 4D Brain MRI Analysis with Deep Learning

This repository contains experiments on **4D medical image analysis** (fMRI, PET, MRI, CT) using **deep learning techniques**. The notebook explores data preprocessing, feature extraction, and model training for tasks like **brain structure analysis and anomaly detection**.

## 📊 Dataset

We use the **IXI Dataset**:

* Brain MRI scans from **3 hospitals in London**.
* Covers multiple modalities: **T1, T2, PD-weighted, DTI**.
* Publicly available at: [IXI Dataset](https://brain-development.org/ixi-dataset/)

## 🧠 Models Implemented

The notebook implements and experiments with:

* **3D CNN** – for spatial feature extraction
* **Variational Autoencoder (VAE)** – for representation learning
* **VAE-GAN** – combining generative power with adversarial learning
* **3D U-Net** – for medical image segmentation

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
```

Make sure you have:

* Python 3.8+
* TensorFlow / PyTorch (depending on model implementation)
* Numpy, Pandas, Matplotlib, Scikit-learn
* NiBabel (for MRI data handling)

## 🚀 Usage

1. Download the **IXI dataset** from the official website.
2. Place the dataset in the `data/` directory.
3. Run the Jupyter Notebook:

```bash
jupyter notebook 4d_mri_analysis.ipynb
```

4. Training starts automatically for the selected model.

## 📈 Results

* **3D CNN** achieved promising accuracy on classification tasks.
* **VAE & VAE-GAN** learned compressed latent representations of MRI scans.
* **3D U-Net** showed strong segmentation performance on structural MRI data.


## 📚 References

* [IXI Dataset](https://brain-development.org/ixi-dataset/)
* Çiçek et al., *3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation* (2016)
* Kingma & Welling, *Auto-Encoding Variational Bayes* (2013)
* Larsen et al., *Autoencoding beyond pixels using a learned similarity metric* (2015)

---

👉 Do you want me to also generate a **requirements.txt** file from the notebook’s imports so your repo is fully ready to run?
