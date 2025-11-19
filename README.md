# Yolo_image
### YOLOv11 Image Search Application

A powerful Computer Vision–powered Image Search Engine built using YOLOv11, Streamlit, and Python.
This application can automatically detect objects in images, generate metadata, and help you search images based on object type and count with an interactive UI.

# 🚀 Features
🔍 Object Detection & Metadata Generation

Process an entire image directory using YOLOv11

Save detection results as structured metadata JSON

# 🧠 Smart Image Search Engine

Search images by:

Selected object classes

OR / AND matching modes

Maximum count thresholds per class

Highlight matching objects in results

# 🖼️ Interactive Image Viewer

Grid-based image layout

Toggle bounding boxes

Highlight matched objects

Rich metadata overlay

# 💾 Export Options

Download search results as JSON

# ⚡ Hardware Support

Works on CPU


Optional CUDA GPU acceleration

🛠️ Installation
🔧 CPU Installation
conda create -n yolo_image_search python=3.11 -y
conda activate yolo_image_search
pip install -r requirements.txt

# ⚡ GPU Installation (CUDA)
conda create -n yolo_image_search_gpu python=3.11 -y
conda activate yolo_image_search_gpu
conda install pytorch==2.5.1 torchvision==0.20.1 pytorch-cuda=12.4 -c pytorch -c nvidia
pip install -r requirements.txt

# CUDA Docs

Linux: https://docs.nvidia.com/cuda/cuda-installation-guide-linux

Windows: https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows
