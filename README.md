# Construction-safety-Open-hole-detection
https://universe.roboflow.com/northeastern-4sfxe/construction-safety-open-hole-excavation-detection
Provided by a Roboflow user
License: CC BY 4.0

This model will be deployed to our Jetson-based edge inference systems for job sites allowing us to monitor and report on unsafe conditions surrounding excavation and earth moving. This model should run on a single-board computer; we will likely combine functionality with the PPE model to determine if somebody is wearing a harness near an unsafe excavation.

The dataset includes 1842 images.
Open-hole are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Random rotation of between -7 and +7 degrees
* Random brigthness adjustment of between -15 and +15 percent
* Salt and pepper noise was applied to 3 percent of pixels

<a href="https://universe.roboflow.com/northeastern-4sfxe/construction-safety-open-hole-excavation-detection">
    <img src="https://app.roboflow.com/images/download-dataset-badge.svg"></img>
</a>
<a href="https://universe.roboflow.com/northeastern-4sfxe/construction-safety-open-hole-excavation-detection/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg"></img>
</a>
