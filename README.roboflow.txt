
Card Detection - v12 2024-06-30 11:45pm
==============================

This dataset was exported via roboflow.com on October 17, 2024 at 12:43 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 6436 images.
Card are annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random brigthness adjustment of between -18 and +18 percent
* Random Gaussian blur of between 0 and 0.5 pixels
* Salt and pepper noise was applied to 0.49 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random shear of between -6° to +6° horizontally and -6° to +6° vertically


