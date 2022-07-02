
Medical Mask Detection - v2 2022-07-02 8:40pm
==============================

This dataset was exported via roboflow.ai on July 2, 2022 at 5:41 PM GMT

It includes 1439 images.
Masks are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 2 versions of each source image:
* Random brigthness adjustment of between -10 and +10 percent

The following transformations were applied to the bounding boxes of each image:
* Random Gaussian blur of between 0 and 2 pixels


