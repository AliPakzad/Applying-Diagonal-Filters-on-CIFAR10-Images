# Applying-Diagonal-Filters-on-CIFAR10-Images


This project demonstrates how simple custom-designed filters affect images from the CIFAR-10 dataset. It focuses on applying two handcrafted 3x3 filters to explore their impact on RGB images.

## 📌 Task Description

- Select the first 10 images from the CIFAR-10 training set.
- Design two 3×3 filters:
  1. The first filter has ones along the **main diagonal**, zeros elsewhere.
  2. The second filter has ones along the **anti-diagonal** (opposite diagonal), zeros elsewhere.
- Apply both filters separately to all 10 selected images using 2D convolution.
- Visualize and compare the original and filtered images using plots.


## 📊 Output

For each image, two filtered versions are shown:
- One after applying the **main diagonal filter**
- Another after applying the **anti-diagonal filter**

All filtered outputs are visualized side by side with the original image for clear comparison.

## 🔍 Purpose

This experiment helps build intuition on:
- How convolution filters interact with image features
- How custom filters can highlight certain structures like diagonal edges
