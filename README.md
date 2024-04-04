# Person_detection_yolov8custommodel
<h1> YOLOv8segmentation_custom_train_model for people detection </h1>

You can download the dataset from "https://universe.roboflow.com/project-uqpx7/people_segmentation_exo"

Ultralytics YOLOv8 is a cutting-edge, state-of-the-art (SOTA) model that builds upon the success of previous YOLO versions and introduces new features and improvements to further boost performance and flexibility. YOLOv8 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and tracking, instance segmentation, image classification, and pose estimation tasks.

We hope that the resources here will help you get the most out of YOLOv8. Please browse the YOLOv8 Docs for details, raise an issue on GitHub for support, and join our Discord community for questions and discussions!

To request an Enterprise License please complete the form at Ultralytics Licensing.

Pip install the ultralytics package including all requirements in a Python>=3.8 environment with PyTorch>=1.8.
pip install ultralytics


Python code

from ultralytics import YOLO

model = YOLO('custom_model.pt')
!yolo task=segment mode=predict model=custom_model.pt source="test_data" conf=0.8

