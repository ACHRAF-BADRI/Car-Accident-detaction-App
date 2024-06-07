# Accident Detection Desktop App

This desktop application detects accidents from video feeds using computer vision and deep learning techniques. It leverages various libraries including NumPy, pandas, OpenCV-Python, TensorFlow, Keras, and Tkinter to accomplish its tasks.

## Features

- **Accident detection from video input**
- **Real-time accident detection**
- **User-friendly GUI using Tkinter**

## Requirements

- Python 3.7
- numpy
- pandas
- opencv-python
- tensorflow
- keras
- tkinter (usually included with Python)

## Model Training

The `model_weights.h5` model used for accident detection is generated from the `training_cnn.ipynb` notebook.

## YOLO v3

Download :
- The `yolov3.weights` file from this link : https://huggingface.co/spaces/Epitech/Scarecrow/blob/main/yolov3.weights 
- Add the Yolo file to the folder "Yolo_Folder".

## Usage

1. **Navigate to the project directory:**

    ```bash
    cd path/to/your/project
    ```

2. **Run the main application file:**

    ```bash
    python main.py
    ```

3. **Login to the application:**
    - Username: `ACHRAF`
    - Password: `aa`

4. **Using the application:**
    - Select a video file or enable the webcam for real-time accident detection through the provided GUI options.
    - The application will analyze video frames or webcam feed for accidents and display detected accidents on the GUI.

5. **Stopping the detection process:**
    - Click the `q` button to stop accident detection.

6. **Viewing accident screens:**
    - Use the provided options to list screens showing detected accidents.

