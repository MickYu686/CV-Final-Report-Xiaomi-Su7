# CV-Final-Report-Xiaomi-Su7
# Requirements: Software
# YOLOv8 Object Detection Project
This project is based on the Ultralytics YOLOv8 framework for object detection tasks, including model inference, testing and result visualization.

1. Requirements: Software
1.1 Basic Environment
- Python: 3.8, 3.9, 3.10 (推荐3.9，兼容性最佳 / Recommended: 3.9 for best compatibility)
- OS: Windows/Linux/macOS (Linux is recommended for training, Windows for testing)

1.2 Install Dependencies
First, clone the repository and enter the project directory:
```bash
# Install PyTorch (match your CUDA version, skip if already installed)
# For CPU-only: pip install torch torchvision torchaudio
# For CUDA 11.8: pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

# Install Ultralytics and other dependencies
pip install -r requirements.txt
# Install Git LFS first (if not installed)
git lfs install
# Clone the repository (will pull LFS-tracked model files)
git clone
