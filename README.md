

# Real-Time Vehicle Detection using YOLOv11X

This project demonstrates real-time vehicle detection leveraging the YOLOv11X object detection model, implemented in a Jupyter Notebook environment.

## Features

- Extracts and prepares a vehicle dataset for training and testing.
- Utilizes the YOLOv11X architecture for accurate and efficient vehicle detection.
- End-to-end workflow: dataset extraction, model setup, training, and inference.
- Suitable for real-time video or image-based vehicle detection tasks.

## Getting Started

1. **Setup**
   - Clone this repository.
   - Ensure you have a GPU-enabled environment (e.g., Google Colab recommended).

2. **Dependencies**
   - Python 3.x
   - Jupyter Notebook
   - Typical ML libraries: `numpy`, `opencv-python`, `matplotlib`, etc.
   - YOLOv11X framework and dependencies (see notebook for details).

3. **Usage**
   - Open `Vehical_Detection.ipynb` in Jupyter or Colab.
   - Follow the notebook cells to extract the dataset, train the model, and run detection.

## Dataset

- The notebook expects a vehicle dataset in ZIP format.
- Configure the path to your dataset in the code (`zip_file_name` and `extraction_path`).

## Results

- The notebook will output detection results on sample images or video, visualizing bounding boxes around detected vehicles.

## Acknowledgements

- YOLO: https://github.com/AlexeyAB/darknet
- Sample vehicle datasets (update with your dataset source if public).

---
