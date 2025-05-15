# FastMRI Brain Project

This project reconstructs fully sampled brain MRI k-space data using nnU-Net.  
We simulate undersampling (e.g., interleaved lines), transform data into the image domain, reconstruct using a neural network, and compare to ground truth using MSE/SSIM.

## Structure

- `data/` : Raw & undersampled data  
- `scripts/` : Preprocessing & inference  
- `results/` : Reconstructed images & metrics

## Author

Yulin Wang – FAU Erlangen-Nürnberg
