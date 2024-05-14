# Computer Vision Course Assignment: Metric Learning with YouTube Commons Dataset

## Overview

Welcome to the Object Tracking assignment for the Computer Vision course! In this assignment, you will be implementing an object tracker using the MOT20 dataset. The goal is to develop a tracking algorithm, evaluate its performance using metrics like HOTA, MOTA, and FPS, and generate a video with bounding boxes for visual evaluation.

### Getting Started

1. **Download a video with labels from the MOT20 dataset:**
   - MOTChallenge website: [MOT20](https://motchallenge.net/data/MOT20/).

2. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/object-tracking-mot-*your-name*
     ```
3. **Navigate to the project directory:**
      ```bash
       cd object-tracking-mot-*your-name*
      ```

### Guidelines

* Dataset:
  * Utilize the MOT20 dataset for this assignment.
  * Ensure that you understand the dataset structure and annotations before proceeding.

* Detector:
  * You can use any pre-trained object detection model which is able to detect pedestrians.
  * **You don't have to train your own model!**

* Tracker:
  * Understand the core principles behind your chosen tracking algorithm.
  * Choose a tracking algorithm such as SORT, DeepSORT, or any other suitable method.
  * Ensure that your implementation integrates well with the MOT20 dataset format.

* Evaluation:
  * Familiarize yourself with the calculation of metrics like HOTA and MOTA to accurately assess your tracker's performance.
  * Evaluate your tracker's performance using metrics like HOTA (Higher Order Tracking Accuracy), MOTA (Multiple Object Tracking Accuracy), and FPS (Frames Per Second).
  * Compare the performance of your tracker with baseline methods if applicable.

* Video Visualization:
  * Generate a video with bounding boxes drawn around the tracked objects with its ids for visual evaluation.
  * Ensure the video showcases the effectiveness of your tracking algorithm.

* Tools and Libraries:
  *  You may use popular libraries such as OpenCV, TensorFlow, or PyTorch for implementing your tracker.
  *  Utilize OpenCV or similar libraries to draw bounding boxes on frames and create the evaluation video.

### Submission

To submit your solution, commit your files to the `main` branch of the repository.

Ensure your final submission includes:
* Source code (main.py or similar) implementing the video and text search functionality.
* Evaluation results presented in a clear format, preferably in a markdown file (report.md or similar).
* The generated video demonstrating the tracked objects with bounding boxes and ids.

### Evaluation

Your solution will be evaluated based on the accuracy of the tracking algorithm and the clarity of your code and documentation.

Best of luck with your assignment! If you encounter any difficulties or have questions, feel free to ask for assistance.
