# Image Sampling in Frequency and Spatial Domains

***Overview***
This project demonstrates image sampling techniques using Python, OpenCV, and NumPy. It compares frequency domain sampling (via Fourier transforms) and spatial domain sampling (via resizing) on grayscale images of a zebra and a peacock. The outputs show how reducing information in different domains affects image quality and reconstruction.

***Features***

### Frequency Sampling
- 	Uses 2D Fast Fourier Transform (FFT) to shift the image into the frequency domain.
- 	Retains only a fraction of low-frequency components (centered mask).
- 	Reconstructs the image using inverse FFT.

### Spatial Sampling
- 	Downsamples the image by a given factor using .
- 	Upsamples back to original size using .
- 	Demonstrates aliasing and loss of detail in spatial domain.

### Automated Output Generation
- 	Saves sampled images for multiple factors ().
- 	Outputs are stored in a dedicated folder: .
