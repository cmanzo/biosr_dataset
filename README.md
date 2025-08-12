# BioSR Dataset (biosr_dataset)

## Overview

This DeepTrackAI repository provides a processed version of the **BioSR** dataset, originally published by [Chang Qiao et al.,  Nature Methods, 2021](https://doi.org/10.1038/s41592-020-01048-5).  
The original dataset consists of paired low-resolution (LR) and high-resolution (HR) fluorescence microscopy images for training and benchmarking super-resolution reconstruction methods.  

The images in this repository have been reformatted and preprocessed to be directly usable in deep learning workflows, while preserving the original content and licensing terms.

### Summary
- **Number of image pairs**:  
  - Training: 40,320 pairs  
  - Testing: 2,080 pairs  
- **Image size**: 128 × 128 pixels  
- **Format**: 8-bit grayscale PNG images  
- **Content**: Each pair contains a low-resolution (LR) and a corresponding high-resolution (HR) image.

---

## Original Source

- **Title**: Evaluation and development of deep neural networks for image super-resolution in optical microscopy  
- **Authors**: Chang Qiao, Yuxiang Li, Junle Qu, et al.  
- **Journal**: *Nature Methods*, 18: 194–202 (2021)  
- **DOI**: [10.1038/s41592-020-01048-5](https://doi.org/10.1038/s41592-020-01048-5)  
- **License**: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

If you use this dataset, please follow the licensing requirements and provide proper attribution to the original authors.

---

## Dataset Structure

```bash
/biosr_dataset  
├── train/  
│   ├── LR/   # Low-resolution training images (PNG)  
│   └── HR/   # High-resolution training images (PNG)  
└── test/  
    ├── LR/   # Low-resolution testing images (PNG)  
    └── HR/   # High-resolution testing images (PNG)  
```

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/biosr_dataset
cd biosr_dataset
```
---

## Attribution

### Cite the original paper:
Qiao C, Li Y, Qu J, et al. *Evaluation and development of deep neural networks for image super-resolution in optical microscopy.* Nature Methods, 18: 194–202 (2021).  
[https://doi.org/10.1038/s41592-020-01048-5](https://doi.org/10.1038/s41592-020-01048-5)

```bibtex
@article{qiao2021biosr,
  title={Evaluation and development of deep neural networks for image super-resolution in optical microscopy},
  author={Qiao, Chang and Li, Yuxiang and Qu, Junle and others},
  journal={Nature Methods},
  volume={18},
  pages={194--202},
  year={2021},
  publisher={Nature Publishing Group},
  doi={10.1038/s41592-020-01048-5}
}
```

---

## License

This dataset is shared under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** License, following the original licensing terms.

