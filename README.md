# hahk_tuffy_edit
This repository will try to make a tuffy only edit from the bollywood movie HAHK. It is a simple object tracker based video trimming applied to create an edit of the movie with only my favourite character of the movie "Tuffy". This is rather simple to do since Tuffy's character is the only dog in the movie.

To perform object tracking, I am using the ultralytics library for object detection. There are options to choose models from. I have chosen Yolov8 which has been trained on COCO dataset with 80 classes. The class_id for 'dog' is 16.


