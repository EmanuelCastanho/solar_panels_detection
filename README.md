# solar_panels_detection

## About

Set of jupyter notebooks created to showcase the detection capabilities of YOLOv8 computer vision model:

*showcase_yolo.ipynb* - A brief introduction to YOLOv8 and example of detection application using one of the default models.

*solar_dataset_preparation.ipynb* - Downloads and prepares a solar panels dataset of very-high resolution WorldView-3 satellite data.

*solar_panels_detection.ipynb* - Trains a YOLOv8 model using the previous solar panels dataset and performs detection.


## Setup

**Create an Anaconda environment:**
```
conda create -n solar_panels_detection-env python=3.10
conda activate solar_panels_detection-env
pip install notebook 
pip install ultralytics==8.1.27
pip install scikit-learn==1.4.1.post1
```
**or open in Colab:**

[![showcase_yolo.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](PLACEHOLDER)

[![solar_dataset_preparation.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](PLACEHOLDER)

[![solar_panels_detection.ipynb](https://colab.research.google.com/assets/colab-badge.svg)](PLACEHOLDER)

## Example

INSERT IMAGE

## References

- **YOLOv8:** Jocher, G., Chaurasia, A., & Qiu, J. (2023). Ultralytics YOLO (Version 8.0.0) [Computer software]. https://github.com/ultralytics/ultralytics
- **Solar Panels Dataset:** https://resources.maxar.com/product-samples/15-cm-hd-and-30-cm-view-ready-solar-panels-germany
- **Solar Panels Labels:** Clark, C. N. (2023). Solar Panels in Satellite Imagery: Object Labels. figshare. Dataset. https://doi.org/10.6084/m9.figshare.22081091.v3
