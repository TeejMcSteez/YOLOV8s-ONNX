# YOLOV8s-ONNX
Google Collab Link to build YOLOV8 ONNX file
[Google Share Link](https://colab.research.google.com/drive/1cZ5_SPLgZXj9l7z4Hg7LLUJyK5crmCDG?usp=sharing)

Orginal file was found at https://github.com/ibaiGorordo/ONNX-YOLOv8-Object-Detection

Many thank's to the author as finding one that worked was awful. 

The only change I made was changing the opset to explicilty be 12, as my frigate instance complained than only opset 12-21 were viable as the default was 22.

I ran this with Google Collab Pro on an A100 so mileage may vary this is mainly to keep for personal use but also for anyone else fighting the issue of not finding a proper .onnx file
