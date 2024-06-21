# Low Light Image Enhancement Project

### Introduction
In recent years, deep learning has revolutionised the field of image processing, particularly in enhancing low-light images. This report presents a project that implements a Convolutional Blind Denoising Network (CBDNet) to address the challenges posed by noisy images captured in low-light conditions and a image post processing method to tackle low light situations and colour correction. CBDNet is designed to first estimate the noise present in the image and then perform non-blind denoising to enhance the image quality. The model's performance is evaluated using the Peak Signal-to-Noise Ratio (PSNR) metric, a widely used indicator of image quality.

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


## Installation Instructions
Follow these steps to set up the environment and run the project:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/AdarshM-07/Low_light_image_Enhancement_Project.git
   cd Low_light_image_Enhancement_Project

2. **Create a Virtual Environment:**
   ```sh
   python -m venv Low_light_image_Enhancement  #     Creates the virtual environment folder
   source Low_light_image_Enhancement/bin/activate  # Activate the virtual environment (Linux/macOS)
   # OR
   Low_light_image_Enhancement\Scripts\activate.bat  # Activate on Windows`
   
  

3. **Install Dependencies:**

   This project requires the following dependencies:
  - [numpy](https://numpy.org/) (>=1.18.5)
  - [TensorFlow](https://www.tensorflow.org/) (>=2.0.0)
  - [OpenCV](https://opencv.org/) (cv2) (>=4.0.0)
  - [matplotlib](https://matplotlib.org/) (>=3.0.0)
  - [glob](https://docs.python.org/3/library/glob.html) (built-in module)
  - [os](https://docs.python.org/3/library/os.html) (built-in module)
    You can install the required packages using `pip`:
    
    ```sh
    pip install numpy tensorflow opencv-python matplotlib


4. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook Model_testing.ipynb
