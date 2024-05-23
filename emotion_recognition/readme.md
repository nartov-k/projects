### Project: Facial emotion recognition
- **Objective**:
  - To train a model (through transfer learning) for recognizing facial emotions through a web-camera in real-time stream;
  - Reach the trade-off between accuracy and computational load.
- **Data Source**: The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/sudarshanvaidya/random-images-for-face-emotion-recognition/data) and combined with my own photos.
- **Tools Used**: 1. Python (Numpy, OpenCV, PyTorch).
- **Outcomes**:
  - Fine-tuned ResNet-50 so it reached 81.94%;
  - Reached the trade-off between decent accuracy and computational load by unfreezing the top FC-classifier and two bottlenecks only.
 
**When you run the code, make sure to update file directions in the notebook code according to your location of files downloaded from this repository**.
