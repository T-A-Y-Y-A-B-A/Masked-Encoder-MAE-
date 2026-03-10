# Masked-Encoder-MAE-
🚀 **Built a Masked Autoencoder (MAE) from Scratch using PyTorch!**

Excited to share my latest project where I implemented a **Self-Supervised Image Representation Learning system using Masked Autoencoders (MAE)**. Instead of learning from labels, the model learns by **reconstructing missing parts of images** — a powerful approach that’s shaping the future of computer vision.

🔍 **What the model does:**
• Takes an image and **masks 75% of its patches**
• A **Vision Transformer encoder** processes only the visible patches
• A **lightweight decoder** reconstructs the missing content
• The model learns meaningful visual representations through **self-supervision**

🛠 **Tech Stack & Implementation Highlights:**
• Built completely using **PyTorch base layers**
• **Vision Transformer (ViT) Encoder + Decoder architecture**
• **Masked MSE Loss** (computed only on masked patches)
• **AdamW Optimizer + Cosine LR Scheduler**
• **Mixed Precision Training** for efficient GPU usage
• **Evaluation with PSNR & SSIM metrics**
• **Interactive Gradio App** for real-time image reconstruction

📊 The project also includes:
✔ Training loss visualization
✔ Reconstruction comparisons (Masked vs Reconstructed vs Original)
✔ A deployable interface to test the model on custom images

This project gave me deeper insight into **self-supervised learning, transformer architectures, and generative vision models** — the same ideas behind models like **DINO, BEiT, and modern foundation vision models**.

📝 **Medium Article:** *https://medium.com/@tayyabaimtiazz/building-a-masked-autoencoder-for-image-reconstruction-with-pytorch-and-gradio-8f0def45b0c1*

I’d love feedback from the community!
What are your thoughts on **self-supervised learning for computer vision?**

