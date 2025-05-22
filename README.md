
# ERD Auto Grader Project

Automated grading system for Entity-Relationship Diagrams (ERDs) using YOLOv8 for object detection, EasyOCR for text extraction, and SBERT for similarity-based matching. Built to streamline TA workflows by reducing manual grading time.

Members:

Tanay Athreya, Nitin Nallagatla, and Samhitha Mupharaphu

This is the README for instructions on how to run our project. 

## Object Detection & OCR Code:

There are final weights for the object detection code using YOLOV8. The code to train the object detection, test it on images, and run the OCR to extract the text is in the .ipynb notebook called ObjectDetection_OCR.ipynb

To run the code, you can run the notebook from top to bottom, but you will have to change file paths to point to the correct paths for images folders and the model weights which we provided.

## Prediction Model using SBERT and Feature Engineering:

To run our prediction model using the results from object detection and OCR, run the .ipynb notebook called ERD_Grade_Prediction_Tool.ipynb from top to bottom, you will have to change the file paths for the files that are in Google Drive. 

