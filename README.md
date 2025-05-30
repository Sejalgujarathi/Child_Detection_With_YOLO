Child Detection with YOLOv8
This project demonstrates how to detect children or people in images using the YOLOv8 object detection model. It allows users to upload images, run inference to detect the person class, annotate the images with bounding boxes, and generate YOLO-format annotation files.
1. Features
Upload and process multiple images.
Detect humans (class 0 in COCO dataset) using YOLOv8.
Annotate images with bounding boxes and confidence scores.
Save annotated images and YOLO-format .txt label files.
Automatically filters for image files only (.jpg, .jpeg, .png, .jfif).

2. Model Used
YOLOv8n – a lightweight, high-speed model ideal for fast inference.
Inference is limited to classes=[0] to detect only persons (useful for child detection use cases).

3. Requirements
Python 3.8+
OpenCV
Ultralytics (for YOLOv8)
Google Colab (recommended for simplicity)

4. Setup
Install the required dependencies:- pip install opencv-python ultralytics

5. How to Use (in Google Colab)
Upload Images:
Run the cell to upload your .jpg, .png, or .jpeg images.

6. Run Detection:
The YOLOv8 model will detect people in each image, draw bounding boxes, and generate corresponding annotation files.

7. Outputs:
Annotated images will be saved in /content/output_images/.
YOLO-format annotation text files will be saved in /content/annotations/.
