# HelmNet Helmet Detection

## Overview  
This project focuses on building a deep learning–based computer vision system to automatically detect whether workers are wearing safety helmets in industrial or construction environments. The solution improves workplace safety monitoring by automating compliance checks and reducing reliance on manual supervision.

## Objective  
The primary goal was to develop an image classification model capable of distinguishing between workers with and without helmets. Such a system enhances safety enforcement, reduces accident risks, and supports real-time safety monitoring at scale.

## Dataset  
- **Source:** Provided as part of the project coursework  
- **Size:** 631 labeled images  
- **Categories:**  
  - `With Helmet` – Workers wearing helmets  
  - `Without Helmet` – Workers without helmets

## Workflow  
1. **Data Preprocessing** – Converted images to grayscale, normalized pixel values, and split data into training, validation, and test sets.  
2. **Model Development** – Built and trained CNN-based classifiers, including a baseline CNN and transfer learning models (VGG-16).  
3. **Model Enhancement** – Applied data augmentation, fine-tuned architectures, and compared model performances.  
4. **Evaluation & Insights** – Selected the best-performing model for deployment in real-world safety applications.

## Results & Key Insights  
- Delivered a highly accurate model for helmet detection across diverse real-world conditions.  
- Enabled scalable, automated safety compliance monitoring.  
- Demonstrated the potential of computer vision in workplace safety and industrial automation.

## Tech Stack  
- **Language:** Python  
- **Libraries:** TensorFlow/Keras, OpenCV, NumPy, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook / Google Colab  

## Author  
**Sandesh S. Badwaik**  
- [LinkedIn](https://www.linkedin.com/in/sbadwaik/)
