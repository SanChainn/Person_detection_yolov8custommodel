# Person_detection_yolov8custommodel
# YOLOv8segmentation_custom_train_model for people detection

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)



## Installation
You can download the dataset from [here](https://universe.roboflow.com/project-uqpx7/people_segmentation_exo).

To install the ultralytics package including all requirements in a Python>=3.8 environment with PyTorch>=1.8, use the following command:
You can check the official website for installation [here](https://docs.ultralytics.com/quickstart/#install-ultralytics)
```
pip install ultralytics

```

## Usage
```
from ultralytics import YOLO

model = YOLO('custom_model.pt')
!yolo task=segment mode=predict model=custom_model.pt source="test_data" conf=0.8
```


