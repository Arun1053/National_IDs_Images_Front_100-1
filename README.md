# National_IDs_Images_Front_100-1
Training yolov4 for custom model and applying pytessearct and easyOCR to extract text


IDE :- Jupyter Notebook

The Project is about gathering National IDs and extract the texts as per classes
We used YOLOv4 to train our custom model so as to get bounding boxes at desired classes mentioned in obj.classes file
To train the model we have to first annotate the data, for which we used labelimg application.


how to use labelimg :- https://youtu.be/p0nR2YsCY_U (check description for source code)

how to train custom yolov4 model :- https://youtu.be/mmj3nxGT2YQ

Now we gather the data and apply our custom yolov4 model get the bounding boxes
Also after that we check which OCR gives the best overall result and apply only that OCR model and convert the extracted text to CSV file


![Screenshot from 2021-06-01 16-13-48](https://user-images.githubusercontent.com/78467404/120310788-63f8f180-c2f4-11eb-9aab-007a656c7cf0.png)


![Screenshot from 2021-06-01 16-11-32](https://user-images.githubusercontent.com/78467404/120310565-25fbcd80-c2f4-11eb-81ee-cdb02bd7efa4.png)
