# Realtime Multiple Object Detection
This project aims to detect multiple objects at once in real-time by just using your browser and a webcam.  
This project uses a pretrained coco-ssd model for object detection. The model takes an image as input and returns class names, bounding box and prediction scores as output. Tensorflow.js model is used to constrain resources used.  

## Example Usage
Below is an example of how it looks when used in a web browser.   
<img src="https://user-images.githubusercontent.com/66838626/158981979-1dfe0cab-8199-4190-944c-b1f3d336b369.png" width="600" height="500">

## Instructions for use
Open the following link https://mithul-joseph.github.io/Object_Detection.github.io/ in your web browser.  
Wait for the model to load after which click the Enable Webcam button.

## Advantages
- the model runs on the browser and no data is sent outside which ensures better privacy for the users.
