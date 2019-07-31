# Character Recognition
It includes the following parts:

## Text Detection (For bounding boxes around any text in an image) 
https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/ 

#Used East Text Detector. This detects the entire text from a given image.
For obtaining the room number alone(and not the other text), you can do it by getting minimum y-valued bounding box. 


## Word segmentation 
https://github.com/githubharald/WordSegmentation

After obtaining the room number, segment the complete room number into individual numbers so that each of them could be sent to the model to predict the room number.


## Prediction
#Used MNIST dataset.
https://github.com/EN10/KerasMNIST 

Train the model using the dataset. Now send each output from the "word segmentation" part to the model to predict room numbers.





