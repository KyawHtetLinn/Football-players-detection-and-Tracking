# Football-players-detection-and-Tracking

Players Detection with FasterRCNN and tracking each player with ByteTrack.

## Results

https://user-images.githubusercontent.com/70162137/228017039-17810309-f262-499d-a257-674b7fb1c56e.mp4 

https://user-images.githubusercontent.com/70162137/228035459-d555f87c-d1e6-4ac4-ba62-c484afd5aa17.mp4

## About Model

* 50 epochs
* [fasterrcnn_resnet50_fpn](https://pytorch.org/vision/main/models/generated/torchvision.models.detection.fasterrcnn_resnet50_fpn.html#fasterrcnn-resnet50-fpn)
* threshold - 0.8 for inference 
* For training, more detail in [this repo](https://github.com/KyawHtetLinn/Football-players-detection-and-Tracking/tree/main/train)
* For inference, in [this repo](https://github.com/KyawHtetLinn/Football-players-detection-and-Tracking/tree/main/inference)

## Loss Metrics

![alt text](https://github.com/KyawHtetLinn/Football-players-detection-and-Tracking/blob/main/assets/Loss.png)



