# Text-Extraction-from-Images
To extract the text fom COCO dataset 

# dependencies :

   1 OpenCv2
   2 Python3
   3 OS
   4 GLOB
   5 Matplot lib
   6 Pandas
   7 Numpy
   
   
# Flow of the project
Step 1: the detect the text in he image and bounding the text and getting the cropped images of the each chareacter
Step 2: To train the the model on the digits and character of englih alphabets and numerals
Step 3: To use the previous trained model for recognizing the character from the previously cropped images.


# Note
* We could have used the pretrained model for the purpose of object detection, but here we are doing each steps from th basic for the detectiong using opencv and its functions of edge deteion and extraction
* Also for the purpose of Text recognition we can use the pretrained model (eg. ReNet) or tresseract or any other api, but, here we are first training the model on characters and numerals and then used the same model for he purpose of text extraction


