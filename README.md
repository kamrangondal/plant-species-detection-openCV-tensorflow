# plant-species-detection-openCV-tensorflow

# Description
Model trained in Tensorflow 2.x then model is converted into tflite model and opened with live stream of openCV to detect the object. Model is trained using custom dataset given on collab,, secondly collab trained model will be converted to the tflite model on collab, then finally download the trained model and run openCV live cam script on windows with trained model in order to detect the species of plant by showing leave in the camera.

# How to do it
- open .ipynb file in google collab, and set tensorflow to GPU, and give your dataset accordingly as instructions are written inside the collab for you. 
* Then, download trained model
+ run the opencv script by this command (in your case, names can be different, so change the command accordingly): **python TFLite_detection_webcam.py --modeldir=custom_model_lite**

# here is link for collab
Open it directly to start working

https://colab.research.google.com/drive/1CgI_jU3ZN3j5hdN1lSKF6-kQ6N92MXd_?usp=sharing
