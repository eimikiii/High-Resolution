# ESRGAN / Real-ESRGAN – Quick Guide

**Real-ESRGAN** is an improved version of ESRGAN for real-world image restoration (e.g., removing JPEG artifacts).  
You can still use original ESRGAN models or your own re-trained ones.

## Features
- Supports **tiles**, **alpha channels**, **grayscale**, and **16-bit** images  
- Includes a **Windows executable** (`RealESRGAN-ncnn-vulkan`) for easy use without Python installation  
- Full training code and model zoo available in the [Real-ESRGAN repo](https://github.com/xinntao/Real-ESRGAN)
all credits to the main creator of ESRGAN
## Quick Test (ESRGAN)
1. **Install requirements**  
   - Python 3, PyTorch ≥1.0  
   - Install packages:  
     ```bash
     pip install numpy opencv-python
     ```
2. **Clone repo**  
   ```bash
   git clone https://github.com/xinntao/ESRGAN
   cd ESRGAN
