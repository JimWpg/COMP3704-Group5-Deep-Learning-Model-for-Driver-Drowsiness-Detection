# <center><font face="Helvetica" font color=orange>Project: Driver Drowsiness Detection Using Deep Learning</font></center>

## Overview
This project aims to develop a deep learning-based system capable of detecting driver drowsiness from frame images. The system uses simple Convolutional Neural Networks (CNNs) and pre-trained ResNet50V2 models to determine the alertness of a driver by analyzing facial and eye states. The trained models are then integrated into OpenCV for real-time detection using a webcam.

<font face="Helvetica">This project is a part of COMP-3704 Neural Networks and Deep Learning, Fall 2024 at ==Red River College Polytechnic[^1]==.</font>

## Dataset
[Driver Drowsiness Dataset (DDD)](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)
https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd

## Team Members
For privacy please refer to the final report.

## Project Goals

- To implement a convolutional neural network (CNN) for static image analysis of driver alertness.
- To implement a pre-trained ResNet50V2 for transfer learning and fine-tuning.
- To integrate pre-trained models like ResNet50V2 for transfer learning.
- To develop a real-time detection system using a laptop's webcam.
- To achieve high accuracy in detecting drowsiness.

## Features

- **Drowsiness Detection**: Use CNN and transfer learning to analyze eye and face states.
- **Real-Time Analysis**: Processes video feed from a webcam to detect drowsiness in real-time.
- **Alert System**: Audio alerts when drowsiness is detected for a set number of consecutive frames.
- **Model Optimization**: Techniques to improve model performance and reduce overfitting.
  
## Results
- Model Performance:
    - Accuracy: 99%
    - Precision: 99%
- Real-Time Detection: Successfully implemented real-time detection with an audio alert system for drowsiness.
## Conclusion
This project significantly improved our academic performance, filled with challenges in dataset management, model building, performance improvement, real-time detection integration, optimization, and collaboration. We met our project goals and gained skills for further research and potential real-world application in driver safety technology. The transition to a local environment and our approach to model training were key to our success, setting a strong foundation for future enhancements and potential commercialization.

## Getting Started
**Prerequisites**
- Python 3.10
- TensorFlow
- keras
- OpenCV
- Playsound
- Docker (optional, for local development)
- Common Libraries
## Installation
1. Clone the repository:
```bash
git clone https://github.com/JimWpg/COMP3704-Group5-Deep-Learning-Model-for-Driver-Drowsiness-Detection.git
cd driver-drowsiness-detection
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Run the real-time detection script:
```bash
python real_time_detection.py
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

[^1]: https://www.rrc.ca/