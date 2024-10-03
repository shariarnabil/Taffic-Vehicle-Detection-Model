# Taffic-Vehicle-Detection-Model
# Traffic Signal Detection using YOLOv3 in Google Colab

This project demonstrates traffic signal detection (red, green, and yellow lights) using the **YOLOv3** deep learning model for real-time object detection. The model processes video frames to detect traffic signals, and the results are visualized directly in **Google Colab** using **Matplotlib**.

## Features

- **YOLOv3 Object Detection**: Utilizes the pre-trained YOLOv3 model for traffic signal detection.
- **Video Upload and Processing**: Allows users to upload videos for processing and detection.
- **Matplotlib Visualization**: Displays detected traffic lights and bounding boxes using Matplotlib in the Google Colab environment.
- **BGR to RGB Conversion**: Converts OpenCV’s BGR format to RGB for proper display in Matplotlib.

## Technology Stack

- **Python**: The primary language used for the project.
- **OpenCV**: Used for video processing and frame manipulation.
- **YOLOv3**: Pre-trained deep learning model for object detection.
- **Matplotlib**: Used for visualizing processed video frames.
- **NumPy**: Utilized for array operations and image handling.

## How to Run the Project

### Prerequisites

Make sure you have the following dependencies installed:

- OpenCV: `pip install opencv-python-headless`
- Matplotlib: `pip install matplotlib`
- wget: `pip install wget`
- Pre-trained YOLOv3 weights and configuration files are automatically downloaded in the code.

### Running the Code in Google Colab

1. **Upload the video**:
   - Use the `files.upload()` function to upload a video file from your local machine to Google Colab.

2. **Run the detection**:
   - The YOLOv3 model will process each frame of the video, detecting traffic lights in real-time. Bounding boxes will be drawn around detected signals, and the labels ("red", "green", etc.) will be displayed on the frames.

3. **View Results**:
   - The processed video frames with detected traffic lights will be displayed using **Matplotlib**.

### Steps to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/traffic-signal-detection-yolov3.git
Navigate to the Project Directory:

bash
Copy code
cd traffic-signal-detection-yolov3
Open in Google Colab:

Open the .ipynb file in Google Colab, upload a video when prompted, and run the cells.
Example Output
Below is an example of a video frame with detected traffic signals:


Files in the Repository
bash
Copy code
|-- traffic-signal-detection-yolov3/
    |-- traffic_signal_detection.ipynb  # Jupyter notebook for YOLOv3 detection
    |-- README.md                       # Project documentation


Author
Your Name - Md Nabil Shariar
