# License Plate Detection with YOLOv12

This project demonstrates a complete workflow for training and deploying a **YOLOv12** object detection model for the task of license plate detection.

The entire process is contained within a notebook (compatible with Kaggle/Google Colab), covering:
* Loading and processing the `keremberke/license-plate-object-detection` dataset from Hugging Face.
* Converting data to the standard YOLO (`.txt`) format.
* Training a `yolov12n` model from pretrained weights.
* Evaluating the model's accuracy on the test set.
* Running inference and visualizing results on both images and videos.

## Model Performance

The `yolov12n` model was trained for 30 epochs, achieving the following results on the test set:

* **mAP50-95:** 0.721
* **mAP50:** 0.988
* **Precision:** 0.994
* **Recall:** 0.971
