# Surgical Instrument Segmentation (SAR-RARP50)

This project contains a U-Net based segmentation pipeline for surgical tool detection using the SAR-RARP50 dataset.

## 📁 Contents

- `src/`: Training, prediction, visualization scripts
- `notebooks/`: Colab notebook with experiments
- `report/`: Final PDF report
- `saved_models/`: Best trained model (`.pth`)

## 🛠 How to Run (Locally)

```bash
python src/train.py
python src/predict.py --video_id video_41
