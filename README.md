# Purpose
In many soccer games, statistics are hard to track manually. With the introduction of the VAR system, officiating in soccer games have improved drastically in accuracy. Player location detection will provide more accurate and advanced metrics.
# Methodology
Data was collected off public datasets from SoccerNet. The data came in json format with individual images that form videos when stitched together. The labels provided the class and the pixel location of each object. The object consists of players, referees and goalkeepers. In this project, I manipulated the data into a yolo format using "class x y w h". Then, I imported the yolov8m model and ran the model using multiple different hyperparameters. In the end, the model achieved 0.07 mAP loss.
