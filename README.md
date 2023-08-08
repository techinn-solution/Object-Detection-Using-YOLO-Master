# Object-Detection-Using-YOLO-Master
# Introduction
YOLO is a single convolutional network that simultaneously predicts multiple bounding boxes and class
probabilities for these boxes. YOLO trains on full images and directly optimizes detection performance.
Along with being fast and efficient one of the major use cases of YOLO is that it can be used on a new
image to predict detections. The base network runs at 45 frames per second with no batch processing
on a Titan X GPU and a fast version runs at more than 150 fps. This also means that we can process
streaming video in real-time with less than 25 milliseconds of latency.
