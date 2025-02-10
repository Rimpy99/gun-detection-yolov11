# Gun Detection using YOLO11

This project uses **YOLO11** to detect guns in images and videos. It can identify different objects and draw bounding boxes in real-time.
The model was trained and tested on Kaggle.

## Features
- **Real-time detection** on images and videos
- **Custom-trained YOLO11 model**
- **Bounding boxes in different colors** for different classes
  - `0` → Firearm (Blue Bounding Box)
  - `1` → Person (Light Blue Bounding Box)
 
## Dataset
The model is trained on a **Gun Detection Dataset** from Roboflow, which includes various images of people holding weapons. Most of these images are from CCTV camera recordings.
https://universe.roboflow.com/pasupathi-jhnnx/gun-detection-abb1h-xxidk

The data used to check how the model performs on unknown data is from: https://www.kaggle.com/datasets/jonathannield/cctv-action-recognition-dataset

## Dependencies
- Ultralytics
- Pillow
- MatPlotLib
