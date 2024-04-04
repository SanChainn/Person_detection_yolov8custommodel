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


## Features
- Feature 1
- Feature 2

## Contributing
Guidelines for contributing to your project.

## License
This project is licensed under the [License Name](LICENSE) - see the LICENSE file for details.




You can download the dataset from here.

Ultralytics YOLOv8 is a cutting-edge, state-of-the-art (SOTA) model that builds upon the success of previous YOLO versions and introduces new features and improvements to further boost performance and flexibility. YOLOv8 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and tracking, instance segmentation, image classification, and pose estimation tasks.

We hope that the resources here will help you get the most out of YOLOv8. Please browse the YOLOv8 Docs for details, raise an issue on GitHub for support, and join our Discord community for questions and discussions!

To request an Enterprise License please complete the form at Ultralytics Licensing.

Installation
Pip install the ultralytics package including all requirements in a Python>=3.8 environment with PyTorch>=1.8.

bash
Copy code
pip install ultralytics
Python code
python
Copy code
from ultralytics import YOLO

model = YOLO('custom_model.pt')
!yolo task=segment mode=predict model=custom_model.pt source="test_data" conf=0.8
Note:
Replace 'custom_model.pt' with the path to your trained custom YOLOv8 model, and 'test_data' with the path to your test data. Adjust the confidence threshold (conf) as needed.
