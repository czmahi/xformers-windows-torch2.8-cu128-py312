
# xFormers for Windows (Torch 2.8.0.dev + CUDA 12.8 + Python 3.12)

Prebuilt `xformers` wheel for Windows 10/11 compatible with:

- **Torch**: 2.8.0.dev20250502+cu128  
- **Torchvision**: 0.22.0.dev20250502+cu128  
- **Torchaudio**: 2.6.0.dev20250502+cu128  
- **CUDA**: 12.8  
- **Python**: 3.12.x (CPython)

---

## ✅ Installation Instructions

directly install the tested version used in this build:
````
pip install https://download.pytorch.org/whl/nightly/cu128/torch-2.8.0.dev20250502%2Bcu128-cp312-cp312-win_amd64.whl
````
Install xformers Wheel

````
pip install https://huggingface.co/czmahi/xformers-windows-torch2.8-cu128-py312/resolve/main/latest-torch2.8-python3.12-xformers-comfyui-windows/xformers-0.0.31%2B8fc8ec5a.d20250503-cp312-cp312-win_amd64.whl
````

## download manully wheel from the link go the then find then downlaod and install
https://download.pytorch.org/whl/nightly/cu128

torchvision-0.22.0.dev20250502+cu128-cp312-cp312-win_amd64.whl

torchaudio-2.6.0.dev20250502+cu128-cp312-cp312-win_amd64.whl

torch-2.8.0.dev20250502+cu128-cp312-cp312-win_amd64.whl


### old version Install PyTorch Nightly (with CUDA 12.8 support)
```bash
pip install --upgrade --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128



# 🧱 xFormers for Windows: Torch 2.8.0.dev + CUDA 12.8 + Python 3.12

## ✅ Installation Guide for xFormers (Torch 2.8.0.dev + CUDA 12.8 + Python 3.12)

This prebuilt wheel is tested and built for:

- ✅ Python **3.12.x**
- ✅ PyTorch **2.8.0.dev (nightly)** with **CUDA 12.8**
- ✅ Windows 64-bit
- ✅ RTX 3000 series cards will work nividia Windows 64-bit
### 🔧 1. Install Python 3.12

Download and install from:  
👉 https://www.python.org/downloads/release/python-3120/

Make sure Python and pip are available in your terminal:

```bash
python --version
pip --version
```

---

### ⚙️ 2. Install Nightly Torch, TorchVision, and TorchAudio

Use the official PyTorch nightly index for CUDA 12.8:

```bash
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
```

> ✅ Confirm version after install:

```bash
python -c "import torch; print(torch.__version__)"
# Should show: 2.8.0.dev + cu128
```

---
## 📦 Installation xformers: 

torchaudio must install 
```bash
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
```

```bash
pip install https://download.pytorch.org/whl/nightly/cu128/torch-2.8.0.dev20250416+cu128-cp312-cp312-win_amd64.whl --no-deps
```

download wheel for local setup: https://download.pytorch.org/whl/nightly/cu128/torch-2.8.0.dev20250416+cu128-cp312-cp312-win_amd64.whl


## 📦 Installation xformers update version : 

before install update version see here for update 

https://github.com/czmahi/xformers-windows-torch2.8-cu128-py312/blob/main/README_xformers_install.md
 
torchaudio must update

 
```bash
pip install --upgrade --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
```
wheel: 

Install directly via `pip` from Hugging Face:

```bash
pip install https://huggingface.co/czmahi/xformers-windows-torch2.8-cu128-py312/resolve/main/xformers-0.0.30+f2de641e.d20250418-cp312-cp312-win_amd64.whl --no-deps
```

✅ No need to build from source or downgrade PyTorch! 


## ⚙️ Build Info

- Built from commit [`c5c0720`](https://github.com/facebookresearch/xformers/commit/c5c0720c0c628539affbcd5332ccc18f813ccafd)
- Compatible with:
  - `torch==2.8.0.dev20250410+cu128`
  - `python==3.12.0`
  - `cuda==12.8`

---

## 🔖 Tags

`windows`, `torch-nightly`, `cu128`, `python312`, `xformers`, `prebuilt`, `xformers-2.8`

---

## 📄 License

This package follows the original [BSD-3-Clause License](https://github.com/facebookresearch/xformers/blob/main/LICENSE).

---

## 🧠 Credits

- Original repository: [facebookresearch/xformers](https://github.com/facebookresearch/xformers)
- Wheel hosted by: [czmahi on Hugging Face 🤗](https://huggingface.co/czmahi/xformers-windows-torch2.8-cu128-py312)

---

### ❤️ Support or Contributions

Open an issue or submit a pull request to help improve this prebuild packaging!
