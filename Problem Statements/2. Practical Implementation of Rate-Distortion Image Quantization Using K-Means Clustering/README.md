# Practical Implementation of Rate-Distortion Image Quantization Using K-Means Clustering

This project implements **color quantization** using **K-means clustering** in RGB space, applied to digital images. It evaluates the trade-off between compression rate and image distortion using metrics like **MSE**, **PSNR**, and **SSIM**.

##  Problem Statement

> Implement k-means clustering-based rate–distortion quantization for the given image.  
> Generate quantized outputs for **K = 2, 4, 6, 8, 10** and evaluate distortion metrics.

##  Input

- Original image: `Problem_Statement_2_Image.jpg` (512 × 512 pixels)
- Format: RGB color image

##  Methodology

1. **Pixel Representation**: Each pixel is treated as a 3D vector in RGB space.
2. **Clustering**: K-means clustering groups pixels into K clusters.
3. **Quantization**: Each pixel is replaced by its cluster centroid.
4. **Evaluation**: Distortion is measured using:
   - **MSE**: Mean Squared Error
   - **PSNR**: Peak Signal-to-Noise Ratio
   - **SSIM**: Structural Similarity Index Measure


##  RGB Palettes

Each K value produces a unique set of RGB centroids. These represent the reduced color palette used for quantization. Centroids are visualized in 3D RGB space.

##  Rate–Distortion Visualization

- **PSNR and SSIM vs K**: Both metrics improve with increasing K, indicating better image fidelity.
- Diminishing returns observed beyond K = 8.


## Tools & Libraries

- Python 3.8+
- `numpy`, `scikit-learn`, `Pillow`, `matplotlib`
- Optional: `scikit-image` for SSIM

##  References

- Gonzalez & Woods, *Digital Image Processing*, 4th Edition
- Scikit-learn documentation: [https://scikit-learn.org](https://scikit-learn.org)
- SSIM metric: Wang et al., IEEE Transactions on Image Processing
