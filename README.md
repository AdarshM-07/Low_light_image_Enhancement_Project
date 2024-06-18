# Low Light Image Enhancement Project

### Introduction
In recent years, deep learning has revolutionised the field of image processing, particularly in enhancing low-light images. This report presents a project that implements a Convolutional Blind Denoising Network (CBDNet) to address the challenges posed by noisy images captured in low-light conditions and a image post processing method to tackle low light situations and colour correction. CBDNet is designed to first estimate the noise present in the image and then perform non-blind denoising to enhance the image quality. The model's performance is evaluated using the Peak Signal-to-Noise Ratio (PSNR) metric, a widely used indicator of image quality.
# Low Light Image Enhancement Project

## Roadmap

| Topic                         | Subtopics                                   | Details                                 |
|-------------------------------|---------------------------------------------|-----------------------------------------|
| **Project Details**           |                                             |                                         |
|                               | **Phase 1: Denoising Low Light Image**      |                                         |
|                               | Data Preparation                            |                                         |
|                               |                                             | Dataset                                 |
|                               |                                             | Image Preprocessing                     |
|                               |                                             | Function                                |
|                               |                                             | Array Conversion                        |
|                               | Architecture and Specifications             |                                         |
|                               |                                             | CBDNet Architecture                     |
|                               |                                             | - Noise Estimation Subnetwork           |
|                               |                                             | - Non-blind Denoising Subnetwork        |
|                               |                                             | Implementation                          |
|                               |                                             | - Tools and Libraries                   |
|                               |                                             | - Training Parameters                   |
|                               | **Phase 2: Increasing Lighting and Colour Correction** |                                  |
|                               | Image Preparation and Enhancement           |                                         |
|                               |                                             | Function                                |
|                               |                                             | - Reading and Resizing                  |
|                               |                                             | - Pixel Range Adjustment                |
|                               |                                             | - Channel Combination                   |
|                               |                                             | RGB Histogram Transformation            |
|                               | Final Enhanced Image                        |                                         |
|                               |                                             | Function                                |
|                               |                                             | - Histogram Equalization                |
|                               |                                             | - Image Blending                        |
| **References**                |                                             |                                         |


Can check out our PSNR values in the results section
