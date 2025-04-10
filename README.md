# Construction-safety-Open-hole-detection
https://universe.roboflow.com/northeastern-4sfxe/open-hole-detection-construction-safety
Provided by a Roboflow user
License: CC BY 4.0

This model is designed for deployment on Jetson-based edge inference systems on job sites, enabling real-time monitoring of unsafe conditions related to excavation and earth-moving activities. The model will be integrated with a PPE detection system to ensure worker safety by checking for harness use near hazardous excavations.

Dataset:
675 Images annotated in the following formats: YOLOv5, YOLOv7, YOLOv8, COCOMO, and Mask R-CNN.

Pre-processing Applied:

* Resize: Images stretched to 640x640

* Classes Modified: Class 0 remapped, Class 1 dropped

* Null Filter: All images must contain annotations.

Augmentation Applied (for YOLOv5 model with highest accuracy):

* Outputs per Training Example: 5

* Flipping: Horizontal

* Rotation: Between -8° and +8°

* Brightness: Between -38% and +38%

* Blur: Up to 1.75px

* Cutout: 7 boxes, 12% size each

The YOLOv5 model achieved the highest accuracy of 81% with these pre-processing and augmentation techniques.

<a href=" https://universe.roboflow.com/northeastern-4sfxe/open-hole-detection-construction-safety">
    <img src="https://app.roboflow.com/images/download-dataset-badge.svg"></img>
</a>
<a href="https://universe.roboflow.com/northeastern-4sfxe/open-hole-detection-construction-safety/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg"></img>
</a>
