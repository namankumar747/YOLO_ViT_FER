# A YOLO-Guided Vision Transformer Framework for Facial Expresion Recognition (FER)

> A YOLO-Guided Vision Transformer Framework for Facial Expression Recognition (FER) is an advanced deep learning approach that combines the strengths of object detection and transformer-based feature learning for accurate emotion recognition. In this framework, YOLO is used to detect and localize facial regions efficiently from input images, reducing background noise and focusing on relevant facial features. The cropped face is then passed to a Vision Transformer (ViT), which captures both local and global facial patterns through self-attention mechanisms. This combination improves recognition accuracy for expressions such as happiness, sadness, anger, surprise, fear, and disgust, making the framework suitable for applications like human-computer interaction, surveillance, and mental health analysis.

## 🔧 Tech Stack
- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch (Torch, Torchvision)
- **Vision Transformer:** timm
- **Object Detection Framework:** Ultralytics YOLO
- **Image Processing:** OpenCV, Pillow
- **Data Processing:** NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Model Evaluation:** Scikit-learn
- **GPU Support:** CUDA 12.1

## 🗂️ Datasets
- CelebA (For Fine-Tuning YOLOv8 model)
- Affectnet (For Fine-Tuning Pretrained Vision Transformer i.e. **vit_base_patch16_224**)


## 🛠️ Project Setup
Follow the steps below to set up the project on your local machine.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/YOLO_ViT_FER.git
cd YOLO_ViT
```

### 2. Create a Python Virtual Environment
In VS code Terminal
```bash
# Create virtual environment
python -m venv FER_env

# Activate virtual environment
# On Windows:
FER_env/Scripts/activate
# On macOS/Linux:
source FER_env/bin/activate
```
### 3. Install Required Libraries
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

## 📝 Notes
- Make sure all dependencies from requirements.txt are installed.
- Make sure that all paths are set correctly.
