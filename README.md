# U-Net MRI Segmentation

This project implements a U-Net architecture in PyTorch to segment brain structures in MRI images. It includes preprocessing, model training, evaluation, and visualization of the segmented outputs.

## 📌 Features

- U-Net implementation in PyTorch
- Dice Loss for segmentation accuracy
- GPU support (optional but recommended)
- Visual comparison of original vs predicted masks

## 🧠 Dataset

The dataset consists of brain MRI images and corresponding segmentation masks. You can use any public brain MRI dataset or replace the `data/` folder with your own.

## 🏃‍♂️ How to Run

1. Install requirements:
    ```bash
    pip install -r requirements.txt
    ```

2. Open the notebook:
    ```bash
    jupyter notebook Copy_of_unet_mri_segmentation.ipynb
    ```

3. Run all cells to train and visualize results.

> ⚠️ Training on CPU is slow. Use a GPU (e.g., Google Colab) for faster performance.

## 🖼️ Sample Results

| Input MRI | Ground Truth | Predicted Mask |
|-----------|--------------|----------------|
| ![](results/output_1.png) | ![](results/output_2.png) | ![](results/output_3.png) |

## 📁 Folder Structure

```
unet-mri-segmentation/
├── Copy_of_unet_mri_segmentation.ipynb
├── requirements.txt
├── README.md
├── results/
│   ├── output_1.png
│   ├── output_2.png
│   └── output_3.png
└── data/
    └── (your training data here)
```

## 🪪 License

MIT License