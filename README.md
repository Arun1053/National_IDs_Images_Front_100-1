# National_IDs_Images_Front_100-1
Training yolov4 for custom model and applying pytessearct to extract text


IDE :- Jupyter Notebook

The Project is about gathering National IDs and extract the texts as per classes
We used YOLOv4 to train our custom model so as to get bounding boxes at desired classes mentioned in obj.classes file
To train the model we have to first annotate the data, for which we used labelimg application.


how to use labelimg :- https://youtu.be/p0nR2YsCY_U (check description for source code)

how to train custom yolov4 model :- https://youtu.be/mmj3nxGT2YQ

Now we gather the data and apply our custom yolov4 model get the bounding boxes and apply pytesseract in it and extract the texts out of images and save it in CSV 
