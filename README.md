# Sign Language Prediction Model
A CNN model that can predict ASL letters to up to 98% accuracy on unseen data. This is compared to the YOLOv5 object detection algorithm that can detect ASL letters to up to 86% accuracy. This project also includes code to load the YOLOv5 model using pytorch and allow real time detections using a webcam via the cv2 library.

The dataset used to train the YOLOv5 model can be found here:
https://public.roboflow.com/object-detection/american-sign-language-letters

The dataset used to train the CNN model can be found here:
https://www.kaggle.com/datasets/grassknoted/asl-alphabet

The test.h5 file if the highest accuracy CNN model and the best.pt is the highest YOLOv5 accuracy model.

