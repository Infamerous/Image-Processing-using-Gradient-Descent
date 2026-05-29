# Image-Processing-using-Gradient-Descent
Noise detection: Finite Difference, Gradient Magnitude, Threshold
k used in the end is 0.001
Consider noisy if Gradient Magnitude > Threshold

Denoise method: Gradient Descent

# Conclusion by Visualization and PSNR
The gradient descent formula can approximate the current pixel to be close to its 4 closest neighbors (horizontal and vertical). When used for denoising, we found out that it may not be suitable with the current code and variable initializations. In the future, with a few tweaks this might be a good algorithm considering it's logic bias and comparation with its neighbor pixels.
