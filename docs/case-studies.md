# deepImageJ Case Studies

This section contains a series of case studies that illustrate the use of deepImageJ in different scenarios. Each case study is a step-by-step guide that explains how to use deepImageJ to solve a specific problem. The case studies are designed to be self-contained and can be followed by anyone with basic knowledge of ImageJ.

## Case Study 1: deepImageJ Pipeline for Integrated Image-to-Image Translation and Nuclei Segmentation

- **Description**: This case study demonstrates the use of deepImageJ for performing image-to-image translation from actin to DAPI images, followed by nuclei segmentation using the StarDist model. The pipeline is then integrated into a macro for batch processing.
- **Files**:
  - `prepare_dataset.py`: Script for preparing the dataset for image-to-image translation and segmentation.
  - `StarDist Postprocess macro CS1.ijm`: ImageJ Macro for StarDist post-processing in Case Study 1.
- **Notebooks**: [Pix2Pix](https://colab.research.google.com/github/HenriquesLab/ZeroCostDL4Mic/blob/master/Colab_notebooks/pix2pix_ZeroCostDL4Mic.ipynb) and [StarDist 2D](https://colab.research.google.com/github/HenriquesLab/ZeroCostDL4Mic/blob/master/Colab_notebooks/StarDist_2D_ZeroCostDL4Mic.ipynb) from ZeroCostDL4Mic.
- **Dataset**: [Pix2Pix, Lifeact-RFP actin stain images](https://doi.org/10.5281/zenodo.3941889) and [StarDist, sir-DNA dapi stain images](https://doi.org/10.5281/zenodo.3715492)
- **Models**: [Pix2Pix for Image Translation from Lifeact-RFP to sir-DNA](https://zenodo.org/records/10405149) and [StarDist Model for Nuclei Segmentation in Synthetic Lifeact-RFP](https://zenodo.org/records/10406307)

### Step by Step Guide
...