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
cd YOLO_ViT_FER
```

### 2. Install Miniconda
Download and install Miniconda3 from the official [Anaconda website](https://www.anaconda.com/download/success).

### 3. Setup Anaconda Environment
```bash
# Open Anaconda Prompt
conda create --name FER_env python=3.9
conda activate FER_env

conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
cd path/to/YOLO_ViT_FER #path to repository folder in local machine

pip install --upgrade pip
pip install --upgrade ipykernel
pip install -r requirements.txt

conda deactivate
```
### 5. Set `FER_env` as the kernel for all Jupyter notebooks.
### 6. Convert `CelebA` Dataset into the standard `YOLOv8` format using the Jupiter notebook `01Annotation_Dataset_Converter.ipynb`

### 7. Fine-Tune and Save all Pretrained Models

### 8. Set the paths of all fine-tuned saved models in the test Jupyter notebooks.
