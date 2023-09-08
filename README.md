# cv-utils
Essential computer vision utilities designed to simplify your OpenCV workflow.
i'll wrap some common tasks in computer vision, making my projects more efficient and the code more elegant

## Features

### 1. video_reader.py
- **VideoReader**: An iterator for effortlessly looping through video frames and extracting them.

The `VideoReader` class accepts the following parameters:

- **file_path** (str): The path to the video file to be read.
- **resize** (tuple, optional): A tuple specifying the desired width and height for resizing the video frames (e.g., `(640, 480)`). If not provided, the frames will not be resized.
- **fps** (int, optional): The frames per second (FPS) at which to read the video. If not provided, the original FPS of the video will be used.
- **duration_seconds** (float, optional): The duration in seconds for which to read the video. If not provided, the entire video will be read.
