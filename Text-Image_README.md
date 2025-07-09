# 🖼️ GLIDE Text-to-Image Generation with Prompt Enhancement and Upscaling

This project showcases the use of [OpenAI's GLIDE (Guided Language to Image Diffusion)](https://github.com/openai/glide-text2im) model to generate images from natural language prompts using diffusion. It further enhances these generated images using various upscaling and filtering techniques to improve visual quality and resolution.

---

## 📌 Project Overview

This notebook-based project allows users to:
- 🔤 Convert natural language prompts like `"pug dog"` into realistic **64x64 images**
- 🔼 Enhance the resolution up to **256x256** using multiple methods
- 🧪 Compare the visual effects of different image enhancement techniques
- 🎨 Visually explore the generative power of text-to-image AI

This solution is especially useful in prototyping, digital art, visual storytelling, and experimentation with generative models.

---

## ✨ Features

- ✅ Text-to-image generation with GLIDE
- ✅ Image upscaling using PyTorch & OpenCV
- ✅ Multiple enhancement methods:
  - Bilinear interpolation
  - Sharpening filter (convolution-based)
  - Bilateral filter (edge-preserving smoothing)
  - Hybrid (upsample + sharpen)
- ✅ Matplotlib visual comparison grid
- ✅ Clean, modular code with clear structure

---

## 🚀 How It Works

### Step 1: 🧠 Text Prompt Encoding
The user enters a text prompt like `"pug dog"` which is tokenized and padded for input into the GLIDE model.

### Step 2: 🎨 Base Image Generation
Using `diffusion.p_sample_loop`, the GLIDE model generates a **64x64 low-resolution image** based on the prompt.

### Step 3: 🔼 Enhancement Methods
The following techniques are used to upscale and enhance the output:

| Method                  | Description                                              |
|-------------------------|----------------------------------------------------------|
| Bilinear Upsampling     | Standard resizing via interpolation                      |
| Sharpening Filter       | Edge enhancement using a convolutional kernel            |
| Bilateral Filtering     | Smooths noise while preserving edges (via OpenCV)        |
| Hybrid (Upsample+Sharpen) | Upsampling followed by sharpening to improve clarity  |

### Step 4: 🖼️ Visualization
The results are displayed side-by-side in a matplotlib figure to compare original and enhanced outputs.

---
![image](https://github.com/user-attachments/assets/cabce438-32a0-43e3-8f75-02fb077ec9c7)

🌱 Future Enhancements
🧠 Enable CLIP-guided generation for higher semantic accuracy
🖼️ Add support for inpainting or image editing with masks
💻 Streamlit/Gradio web interface for real-time text-to-image generation
🔁 Prompt batch processing or style mixing

## 🛠️ Installation

### 1️⃣ Clone the repository

git clone https://github.com/openai/glide-text2im.git
cd glide-text2im

pip install git+https://github.com/openai/glide-text2im
pip install torch torchvision matplotlib opencv-python



---
📜 License
This project is based on OpenAI’s GLIDE repository and follows the MIT License.

Author :
Parimala Dharshini
🔗 [LinkedIn Profile](https://www.linkedin.com/in/parimala-dharshini-903b4a271)
