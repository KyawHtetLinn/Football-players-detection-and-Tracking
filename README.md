# Football-players-detection-and-Tracking

Training FasterRCNN to detect football players with pytorch and tracking each player with ByteTrack.

The model will detect - 
* player
* referee 
* ball
* goalkeeper

## Test Results

https://user-images.githubusercontent.com/70162137/228017039-17810309-f262-499d-a257-674b7fb1c56e.mp4 

https://user-images.githubusercontent.com/70162137/228035459-d555f87c-d1e6-4ac4-ba62-c484afd5aa17.mp4

## About Model

* 50 epochs
* [fasterrcnn_resnet50_fpn](https://pytorch.org/vision/main/models/generated/torchvision.models.detection.fasterrcnn_resnet50_fpn.html#fasterrcnn-resnet50-fpn)
* threshold - 0.8 for inference 
* For training, more detail in [this notebook](https://github.com/KyawHtetLinn/Football-players-detection-and-Tracking/tree/main/train)
* For inference, in [this notebook](https://github.com/KyawHtetLinn/Football-players-detection-and-Tracking/tree/main/inference)

## Dataset

  The training dataset is the [roboflow dataset](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc/dataset/2).For inference, the first video is trimmed from the [Man city-Tottenham highlight](https://youtu.be/xD6uRCW3wpM) and the second test video is from [Kaggle Test Dataset](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data).

## Loss Metrics

![alt text](https://github.com/KyawHtetLinn/Football-players-detection-and-Tracking/blob/main/assets/Loss.png)

## Reference 

* [Track Football Players with Computer Vision](https://blog.roboflow.com/track-football-players/)
* [ByteTrack](https://github.com/ifzhang/ByteTrack)


