
## ✅ Installation Guide for xFormers (Torch 2.8.0.dev + CUDA 12.8 + Python 3.12)

This prebuilt wheel is tested and built for:

- ✅ Python **3.12.x**
- ✅ PyTorch **2.8.0.dev (nightly)** with **CUDA 12.8**
- ✅ Windows 64-bit

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
pip install --upgrade --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
```

> ✅ Confirm version after install:

```bash
python -c "import torch; print(torch.__version__)"
# Should show: 2.8.0.dev + cu128
```

---

### 📦 3. Install This xFormers Build

Now install the `.whl` directly:

```bash
pip install https://huggingface.co/czmahi/xformers-windows-torch2.8-cu128-py312/resolve/main/xformers-0.0.30+f2de641e.d20250418-cp312-cp312-win_amd64.whl --no-deps
```

---

### 🚀 That's it!

You're now ready to use xFormers with memory-efficient attention and CUDA acceleration on Windows for:

- ComfyUI
- Diffusion models
- Custom attention workflows
- Wan 2.1 + SageAttention
- FlashAttention v2+ (if supported)

---

### 🛠️ Troubleshooting

- ❌ **"not a supported wheel" error?**  
  Check Python version is 3.12 and Torch version is exactly 2.8.0.dev + cu128.
  
- ❌ **Conflict with pip packages?**  
  Use `--no-deps` to avoid overwriting nightly Torch builds.
