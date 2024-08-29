# Byakugan

Byakugan is a real-time object detection project that utilizes the YOLO (You Only Look Once) algorithm with OpenCV to detect objects in a webcam feed. The project is named after the famous "Byakugan" from the anime Naruto, symbolizing its ability to detect objects with precision.

## Features

- **Real-time object detection**: Uses the YOLOv3 model to detect objects in a live webcam feed.
- **Bounding boxes and labels**: Draws bounding boxes around detected objects and labels them with their respective classes and confidence scores.
- **Non-Max Suppression (NMS)**: Filters overlapping bounding boxes to retain only the most accurate detections.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/masoomul786/Byakugan.git
    cd byakugan
    ```

2. **Install the required libraries**:
    ```bash
    pip install opencv-python numpy
    ```

## Usage

1. **Run the script**:
    ```bash
    python byakugan.py
    ```

2. **Start detecting**:
    - The webcam will open, and you will see objects detected in real-time with bounding boxes and labels.
    - Press `q` to exit the detection loop.

## Configuration

- **Confidence Threshold**: Adjust the `confidence` value in the code to change the sensitivity of the object detection.
- **NMS Threshold**: Modify the `nms_threshold` to control the degree of overlap allowed between bounding boxes.

## Example Output

![Byakugan Example](![Picsart_24-08-30_02-21-10-245 (1)](https://github.com/user-attachments/assets/853b47d3-17d8-4cca-adaa-082b38d3f52b)


## License

This project is licensed under the MIT License - see the [LICENSE](main/LICENSE) file for details.

## Acknowledgments

- [YOLO (You Only Look Once)](https://pjreddie.com/darknet/yolo/)
- [OpenCV](https://opencv.org/)
- [COCO Dataset](https://cocodataset.org/)
