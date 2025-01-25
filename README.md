# Whole-Body Bone Scan Dataset (BS-80K)

This repository contains information about the dataset and methodology used in the study of whole-body bone scans for identifying metabolic abnormalities. The dataset originates from **BS-80K**, a collection of bone scan images curated at West China Hospital.

## Dataset Description

The dataset used in this study is derived from BS-80K and contains a total of **3,253 whole-body bone scan images**, categorized into the following:

- **Anterior images**: 2,924 images with bounding box annotations.
- **Posterior images**: 2,555 images with bounding box annotations.

### Classes
The dataset consists of **three distinct classes**:
1. **Background**
2. **Abnormal** (regions indicative of abnormal metabolic activity)
3. **Normal**

### Image Specifications
- **Resolution**: Each image is 256 x 1024 pixels.
- **Annotations**: Bounding box annotations are provided for precise segmentation and accurate identification of areas of interest.

## Importance of Bounding Box Annotations

The bounding box annotations in this dataset are essential for:
1. **Precise Segmentation**: Helping delineate regions of interest for further analysis.
2. **Accurate Identification**: Supporting the detection of abnormal metabolic activity in whole-body bone scans.

## Reference Study

This dataset and methodology are part of a study conducted at West China Hospital. You can find more details in the original paper:

- **Paper Title**: [Deep Learning-Assisted Detection of Metabolic Abnormalities in Whole-Body Bone Scans](https://pubmed.ncbi.nlm.nih.gov/36334360/)
- **Published On**: PubMed

## Usage

Researchers and practitioners can use this dataset for tasks such as:
- **Image Classification**
- **Object Detection**
- **Medical Image Segmentation**

If you utilize this dataset, please make sure to cite the original study appropriately.

---

## Citation

Please cite the paper if you use this dataset in your research:

```plaintext
[13] Deep Learning-Assisted Detection of Metabolic Abnormalities in Whole-Body Bone Scans, PubMed ID: 36334360.
