# SA-YOLO: Spectral-Aware YOLOv11 Network for Infrared Dim and Small Target Detection
<img width="991" height="879" alt="image" src="https://github.com/user-attachments/assets/23bb8a9d-142c-4a8b-8e9f-1906fd7dc4f4" />

## 1. Dataset Download
### 1.1 ISUAV-D Dataset
- **Baidu Netdisk**: [Download Link](https://pan.baidu.com/s/1u2ch4_uY9lnJ28tY3-8x9g)
- **Extraction Code**: `SAYO`
- 
### 1.2 Other Supported Datasets
| Dataset Name | Official Source |
|--------------|-----------------|
| NUAA-SIRST | [GitHub Repository](https://github.com/YimianDai/sirst) |
| IRSTD-1K | [GitHub Repository](https://github.com/RuiZhang97/ISNet#ppt-setting-and-p3m-10k-dataset) |
| NUDT-SIRST | [Baidu Netdisk](https://pan.baidu.com/s/1WdA_yOHDnIiyj4C9SbW_Kg?pwd=nudt) (Password: `nudt`) |
| NUST-SIRST | [GitHub Repository](https://github.com/wanghuanphd/MDvsFA_cGAN) |
| IST-A | [GitHub Repository](https://github.com/SeaHifly/Infrared-Small-Target) |

## 2. Code Execution
### 2.1 Dataset Preparation
Place downloaded datasets in:

### 2.2 Model Training
Run the training script:
bash
python train_detect.py

### 2.3 Output Files
Trained models will be saved in:
./ultralytics-main/runs/train/

## 3. Citation
If you use ISUAV-D dataset in your research, please cite this paper.
