# ORCA: Oceanic Recognition & Classification Application for sea-life analysis systems.
[![Python](https://img.shields.io/pypi/pyversions/tensorflow.svg)](https://badge.fury.io/py/tensorflow) [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) ![Maintainer](https://img.shields.io/badge/maintainer-@louisbrulenaudet-blue)

The Oceanic Recognition & Classification Application (ORCA) is a fine-tuned Region-based Convolutional Neural Network (RCNN) project designed to push the boundaries of automated sea-life detection and segmentation analysis. Our aim is to provide an advanced tool that meets the rigorous demands of marine research and conservation efforts globally. It uses selective search to identify a number of bounding-box object region candidates (“regions of interest”), and then extracts features from each region independently for classification.

This document is intended to guide users, collaborators, and researchers in the utilization and further development of ORCA, enabling the collective advancement of marine exploration and preservation endeavors.

![Plot](https://github.com/louisbrulenaudet/orca/blob/main/thumbnail.png?raw=true)

## Core dependencies

Below is a list of the primary libraries used in ORCA:

- `gradio`: An easy-to-use library for creating customizable UI components for machine learning models.
- `cv2` (OpenCV): An open-source computer vision and machine learning software library.
- `torch`: The PyTorch library, a popular machine learning framework that provides a wide range of algorithms for deep learning.

### Detectron2 Installation

The ORCA project utilizes `detectron2`, a library that provides state-of-the-art algorithms for object detection. Due to potential complexities in the installation process of `detectron2`, a try-except block is employed to ensure that the library is installed correctly. If `detectron2` is not found, it will be installed directly from a specified GitHub repository.

If you encounter any issues during installation, you may need to install `detectron2` manually. Instructions provided by the detectron2 repository can guide you through this process.

### Additional Notes

Keep in mind that the installation of the PyTorch library (`torch`) and `detectron2` may depend on your specific hardware configuration, especially the type of GPU if available. Ensure that you have the correct versions of CUDA and cuDNN installed and configured to match the requirements of the libraries for optimal performance.

It is advisable to check the official websites of PyTorch and detectron2 for the most up-to-date installation instructions tailored to your setup.

## Citing this project
If you use this code in your research, please use the following BibTeX entry.

```BibTeX
@misc{louisbrulenaudet2024,
	author = {Louis Brulé Naudet},
	title = {ORCA: Oceanic Recognition & Classification Application for sea-life analysis systems},
	howpublished = {\url{https://github.com/louisbrulenaudet/orca}},
	year = {2024}
}

```
## Feedback
If you have any feedback, please reach out at [louisbrulenaudet@icloud.com](mailto:louisbrulenaudet@icloud.com).