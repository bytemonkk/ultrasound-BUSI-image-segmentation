# Breast Ultrasound Image Segmentation Datasets

This project evaluates **HEMF-Net** on multiple benchmark breast ultrasound image segmentation datasets. Due to dataset licensing restrictions and repository size limitations, the datasets are not included in this repository.

---

# 1. BUSI Dataset

### Dataset Name

Breast Ultrasound Images Dataset (BUSI)

### Description

BUSI is one of the most widely used breast ultrasound datasets for lesion classification and segmentation research. The dataset contains benign, malignant, and normal breast ultrasound images along with corresponding lesion masks.

### Download Link

https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset

### Reference

Al-Dhabyani W, Gomaa M, Khaled H, Fahmy A.

Dataset of Breast Ultrasound Images.

Data in Brief, 2020.

---

# 2. BUS-BRA Dataset

### Dataset Name

BUS-BRA

### Description

BUS-BRA is a large-scale breast ultrasound benchmark dataset developed for lesion segmentation and classification research. The dataset contains expert-annotated ultrasound images collected from multiple clinical cases.

### Download Link

https://zenodo.org/records/8231412

### Reference

BUS-BRA Dataset Authors.

Large-Scale Breast Ultrasound Benchmark Dataset.

---

# 3. BrEaST Dataset

### Dataset Name

BrEaST Ultrasound Dataset

### Description

BrEaST is a publicly available breast ultrasound dataset designed for computer-aided diagnosis and segmentation studies. The dataset provides breast ultrasound images and corresponding lesion annotations.

### Download Link

https://www.kaggle.com/datasets/mohamedbenticha/breast-lesions-ultrasound-image-dataset

### Reference

BrEaST Dataset Authors.

Breast Ultrasound Lesion Analysis Dataset.

---

# Dataset Organization

After downloading the datasets, organize them as follows:

```bash
datasets/
│
├── BUSI/
│   ├── images/
│   └── masks/
│
├── BUS-BRA/
│   ├── images/
│   └── masks/
│
└── BrEaST/
    ├── images/
    └── masks/
```

---

# Datasets Used in This Study

| Dataset | Application         |
| ------- | ------------------- |
| BUSI    | Lesion Segmentation |
| BUS-BRA | Lesion Segmentation |
| BrEaST  | Lesion Segmentation |

---

# Notes

* Images should be resized and normalized before training.
* Data augmentation can be applied during training.
* Ground-truth masks are required for segmentation evaluation.
* Please follow the original dataset licenses and usage policies.

---

# HEMF-Net Evaluation

The proposed HEMF-Net framework is evaluated across:

* BUSI Dataset
* BUS-BRA Dataset
* BrEaST Dataset

to assess segmentation performance, boundary delineation capability, and cross-dataset generalization.
