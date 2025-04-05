# Medical Imaging

This repository contains projects developed during a graduate-level medical imaging module. It covers practical applications of image reconstruction, denoising, and radiomic analysis using real medical imaging data from PET, CT, and MRI.

---

## Contents

### 1. PET-CT Image Reconstruction
- **Goal:** Reconstruct CT and PET images from raw sinogram data
- **Techniques:**  
  - Filtered Back Projection (FBP)  
  - OS-SART for CT  
  - OSEM for PET  
- **Additional Work:**  
  - Attenuation correction using CT-derived maps  
  - Comparison with MLEM  
  - Visualization of aligned PET-CT reconstructions
---

### 2. MRI Denoising from k-Space (Multi-Coil)
- **Goal:** Visualize and denoise MRI knee data from raw k-space
- **Steps:**
  - Coil-wise reconstruction using FFT
  - Combined image reconstruction (root-sum-of-squares)
  - Denoising in both image space (Gaussian, bilateral, wavelet) and k-space (Butterworth filter)
- **Outcome:** Comparison of denoising methods and their effect on image quality

---

### 3. CT Lung Nodule Segmentation & Classification (LIDC-IDRI)
- **Goal:** Segment lung nodules and classify them as benign or malignant
- **Steps:**
  - Load NIfTI images and masks
  - Apply custom intensity-based thresholding
  - Extract radiomic features (Energy, MAD, Uniformity)
  - Analyze distributions by class

---

## Data

- CT segmentation uses a chosen subset of public data from [LIDC-IDRI](https://www.cancerimagingarchive.net/collection/lidc-idri/)
- MRI and PET-CT data not included in this repository due to size/privacy
- Visual outputs and code are available in the notebooks

---

## Acknowledgments

- This project was originally developed as part of a graduate-level medical imaging course at the University of Cambridge.


