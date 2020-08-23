# Hazard Detection for Self-Driving cars using Monocolar camera feed


Uses the [Tensorflow Object Detection API](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1.md) to run the following models

- Object detection and classification according to  predefined classes producing bounded boxes, object classes and detection scores.
- Multiple Object Tracking of Detected objects
- Trajectory prediction for each detected object
- A 3-Dimensional location (x,y,z) estimator using information from the object detection (bounded boxes) of all detected objects.

## Requirements

- Python 3.6+
- Tensorflow 2.*
- PIP

## Running the models
The main notebook to run is the hazard_detection notebook. This contains everything mentioned above in a single notebook. GPU is required for inferences to be made in good time.

## Dataset
The dataset is configured for the KITTI Tensorflow Dataset, stored in a private Google Cloud Storage. (May be removed in a few months)


### Acknowledgements
Uses [SORT Algorithm](https://github.com/abewley/sort) by Alex Bewley

Uses some parts from [KITTI distance estimation](https://github.com/harshilpatel312/KITTI-distance-estimation)


