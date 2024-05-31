# Vessel Segmentation and Occlusion Detection in CT Angiography Images

This project involves the development of a computational tool for segmenting blood vessels and detecting potential occlusions in contrast-enhanced CT angiography images. The tool aims to enhance early diagnostic capabilities for vascular abnormalities.

## Overview

The main objective of this project is to provide a robust and efficient method for segmenting blood vessels and detecting occlusions in CT angiography images. By integrating advanced image processing techniques and leveraging the power of OpenAI's GPT-4 model for interactive query responses, this tool aids in the early diagnosis of vascular conditions.

## Features

- **Vessel Segmentation:** Uses Gaussian Blurring, CLAHE, and adaptive thresholding to accurately segment blood vessels in CT images.
- **Occlusion Detection:** Identifies potential occlusions within the segmented vessels.
- **Interactive Interface:** Implements a ChatGPT interface using OpenAI's GPT-4 model to answer user queries about the processed images.

## Methodology

1. **Preprocessing:**
   - Apply Gaussian Blurring to reduce noise and smooth the images.
   - Use CLAHE (Contrast Limited Adaptive Histogram Equalization) to enhance image contrast.
   - Perform adaptive thresholding to segment the blood vessels.

2. **Occlusion Detection:**
   - Analyze the segmented vessels to detect potential occlusions.
   - Utilize image processing techniques to highlight occluded regions.

3. **Interactive Interface:**
   - Integrate OpenAI's GPT-4 model to provide an interactive query-response system for users to ask questions about the processed images.

## Technologies Used

- **Programming Languages:** Python
- **Libraries:** OpenCV, NumPy, Pandas
- **Machine Learning:** OpenAI's GPT-4
- **Image Processing Techniques:** Gaussian Blurring, CLAHE, Adaptive Thresholding

## Getting Started

### Prerequisites

- Python 3.7 or higher
- OpenCV
- NumPy
- Pandas
- OpenAI API key (for GPT-4)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ct-angiography-segmentation.git
   cd ct-angiography-segmentation
