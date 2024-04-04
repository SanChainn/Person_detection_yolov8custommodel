# Person_detection_yolov8custommodel
# YOLOv8segmentation_custom_train_model for people detection

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)


## Installation
You can download the dataset from [here](https://universe.roboflow.com/project-uqpx7/people_segmentation_exo).

To install the ultralytics package including all requirements in a Python>=3.8 environment with PyTorch>=1.8, use the following command:
```
pip install ultralytics
pip install Python >=3.8
pip install torch>=1.8
```

## Usage
```
from ultralytics import YOLO

model = YOLO('custom_model.pt')
!yolo task=segment mode=predict model=custom_model.pt source="test_data" conf=0.8
```


