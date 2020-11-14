# You only look once (YOLO) is a state-of-the-art, real-time object detection system that is  extremely fast and accurate. 
In mAP measured at .5 IOU YOLOv3 is on par with Focal Loss but about 4x faster. Moreover, you can easily tradeoff between speed and accuracy simply by changing the size of the model, no retraining required!
# Prior detection systems repurpose classifiers or localizers to perform detection. 
They apply the model to an image at multiple locations and scales. High scoring regions of the image are considered detections.
YOLO uses a totally different approach. It applies a single neural network to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.
# This model has several advantages over classifier-based systems. It looks at the whole image at test time so its predictions are informed by global context in the image. 
It also makes predictions with a single network evaluation unlike systems like R-CNN which require thousands for a single image.
# Weights and Config Files Uploaded in Data
The link to access the weights and the configuration file for this project are present in the data folder. 
