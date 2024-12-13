# Multi-Model-Image-Colorization-System-with-Interactive-Dashboard-and-Performance

README for Multi-Model Image Colorization System
Project Overview
The Multi-Model Image Colorization System converts grayscale images to color
using three models:
1. OpenCV (custom)
2. Autoencoder (custom)
3. DeOldify (pre-trained)
The system features an interactive dashboard (built with Streamlit and Gradio)
and supports performance evaluation using PSNR, SSIM, and MSE.
Project Structure
![image](https://github.com/user-attachments/assets/f2f7b18f-41af-4ad0-9b7f-6d3c5d5d9a13)
Installation
Run the following commands to install required libraries:
• pip install opencv-python-headless torch torchvision numpy ffmpeg yt_dlp
• pip install scikit-image tensorflow lpips streamlit pyngrok gradio pillow fastai
matplotlib
Usage
1. Run Dashboard:
• streamlit run dashboard.py
2. Upload Image:
• Upload a grayscale image in JPG/PNG format.
• View results from all 3 models (OpenCV, Autoencoder, DeOldify).
3. View Metrics:
• Evaluate PSNR, SSIM, and MSE scores for each model.
System Workflow
1. Image Upload: User uploads a grayscale image.
2. Model Inference:
o OpenCV
o Autoencoder
o DeOldify: Applies a tuned pre-trained model for improved artistic
colorization.
3. Evaluation: Computes PSNR, SSIM, MSE for model comparison.
4. Dashboard Display: Outputs colorized images, metrics, and comparisons.
Evaluation Metrics
1. PSNR: Measures signal-to-noise ratio between images.
2. SSIM: Measures structural similarity of images.
3. MSE: Calculates mean squared error between images.
These metrics allow for objective comparison of model performance.
Dashboard Features
• Image Upload: Upload and visualize grayscale images.
• Model Colorization: View colorized images from PyTorch, Autoencoder, and
tuned DeOldify.
• Performance Metrics: View PSNR, SSIM, and MSE scores
