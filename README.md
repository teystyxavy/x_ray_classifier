# x_ray_classifier

## File details:
1. classifier.ipynb - contains code of training classification model using yolo11-cls models

2. segmentation_person.ipynb - contains code for training segmentation model to extract person from image for further training of classification model - uses yolo11-seg models

3. segmentation_classes.ipynb - contains code for training segmentation model to extract classes from image - uses yolo11-seg models

4. realtime_processing.ipynb - contains code for real time processing of videos and images using classification, segmentation, object detection and finally pose-estimation + light detection (BEST) using yolo11 models

5. mediapipe.ipynb - contains code for real time processing of videos and images using mediapipe

## to run code:
create a virtual environment and install the required dependencies as specified in requirements.txt by running the command '''pip install -r requirements.txt'''. 

note: for mediapipe.ipynb, mediapip and ultralytics have dependency conflicts, which were resolved by installing them in a temporary runtime environment in Google Colab.