# Virtual-Lipstick-Try-On-System-Using-MATLAB-and-Image-Processing
This project implements a Virtual Lipstick Try-On System using MATLAB and image processing techniques. The system allows users to visualize different lipstick shades by detecting and recoloring lips in an image using HSV color space.
**Overview**

This project uses image processing to detect lips using HSV color space, applying custom colors to simulate different lipstick shades. It is useful for virtual makeup applications.

**Features**

Lip region detection using HSV color thresholding.

Virtual lipstick application with customizable shades.

Visualization of the original and edited images.

Simple and efficient MATLAB implementation.

**How It Works**

Image Loading: The input image is read using imread().

Color Space Conversion: The RGB image is converted to HSV using rgb2hsv().

Lip Detection: A binary lip mask is created using defined HSV thresholds.

Color Application: The hue and saturation values in the lip region are adjusted.

Display Results: The modified image is converted back to RGB and displayed using imshow().

**Results**

Original Image: Displayed first for reference.

HSV Image: Visualizes the image in HSV space.

Lip Mask: Binary mask highlighting detected lips.

Output Image: Final image with applied lipstick color.

**Customization**

Change the desired lipstick color by adjusting the color variable (e.g., 0.05 for red, 0.8 for purple).

Adjust saturation using hsvImage(:,:,2) to fine-tune the effect.

