# GrassLiv-3: A UAV-Based Grassland Livestock Detection Dataset

**GrassLiv-3** is a high-resolution unmanned aerial vehicle (UAV) imagery dataset designed for livestock detection in grassland environments. It contains **568 UAV images** with **40,811 annotated instances** across three livestock categories: **cattle, horses, and sheep**.

The dataset was collected from several grassland regions in Inner Mongolia, China. It encompasses diverse environmental conditions and challenging detection scenarios, including small objects, dense livestock distributions, partial occlusions, and complex background textures.

GrassLiv-3 was developed as part of the research presented in:

**DAFS-YOLO: Dense-Aware Feature Enhancement for UAV-Based Grassland Livestock Detection in Dense Sheep Scenes**

---

## 1. Dataset Overview

GrassLiv-3 is intended to support research on UAV-based livestock detection, small-object detection, dense object detection, and livestock population monitoring.

### Key Features

- **High-resolution UAV imagery:** Images captured at different flight altitudes and spatial resolutions.
- **Three livestock categories:** Cattle, horses, and sheep.
- **Dense object distributions:** Includes scenes containing hundreds or even thousands of livestock instances.
- **Challenging detection conditions:** Small targets, overlapping objects, complex grassland textures, and background interference.
- **Object detection annotations:** Bounding-box annotations provided in YOLO format.

## 2. Dataset Statistics

GrassLiv-3 contains a total of **568 images** and **40,811 annotated livestock instances**.

| Category | Number of Instances |
|:---|---:|
| Cattle | 4,541 |
| Horse | 1,185 |
| Sheep | 35,085 |
| **Total** | **40,811** |

The dataset covers four grassland regions in Inner Mongolia, China:

- Jarud Banner
- West Ujimqin Banner
- Horqin Right Front Banner
- Evenki Autonomous Banner

The UAV images were collected between July and September 2025 using DJI Mavic series drones.

The original images have varying spatial resolutions, including 4000 × 3000, 5280 × 3956, and 8064 × 6048 pixels.

## 3. Dataset Structure

The dataset provides UAV images and corresponding bounding-box annotations in YOLO format.

Each annotation follows the standard YOLO representation:

`class_id x_center y_center width height`

Bounding-box coordinates are normalized relative to image dimensions.

### Dataset Classes

| Class ID | Category |
|:---:|:---|
| 0 | Cattle |
| 1 | Horse |
| 2 | Sheep |

## 4. Data Access

GrassLiv-3 is hosted on **Hugging Face**.

**Dataset Repository:** [GrassLiv-3 on Hugging Face](https://huggingface.co/datasets/sunshineofyou/GrassLiv-3)

The dataset is distributed through a gated-access repository. Researchers interested in accessing the complete dataset should submit an access request through Hugging Face.

Access requests are reviewed by the dataset maintainers.

### How to Request Access

1. Visit the Hugging Face dataset repository.
2. Sign in to your Hugging Face account.
3. Complete the dataset access request form.
4. Submit your request for review.
5. Once approved, download the dataset archive from the repository.

The released dataset includes original-resolution UAV imagery and corresponding object detection annotations.

## 5. Applications

GrassLiv-3 can support research in:

- UAV-based livestock detection
- Small-object detection
- Dense object detection
- Livestock counting and population estimation
- Remote sensing image analysis
- Deep learning for precision livestock management

## 6. Citation

If you use GrassLiv-3 in your research, please cite the associated publication.

```bibtex
@article{DAFSYOLO,
  title   = {DAFS-YOLO: Dense-Aware Feature Enhancement for UAV-Based Grassland Livestock Detection in Dense Sheep Scenes},
  author  = {Shuwei Huang,Jingguo Lv,Boyu Wang,Beibei Shen},
  journal = {AgriEngineering},
  year    = {2026},
  doi     = {10.3390/agriengineering8090363}
}
```

Please replace the bibliographic placeholders with the official publication information.

## 7. License

The licensing terms for GrassLiv-3 are specified in the Hugging Face dataset repository.

**Dataset License:** [Creative Commons Attribution 4.0 International (CC BY BN 4.0)](https://spdx.org/licenses/CC-BY-NC-4.0)

Please review the license before using or redistributing the dataset.

The associated DAFS-YOLO implementation, if released, may be subject to a separate software license.
