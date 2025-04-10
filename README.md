# Sign_Language
 
# Sign Language Recognition using MediaPipe and Random Forest Classifier — Intel oneAPI Optimised Scikit-Learn Library
## Problem Statement
American sign Language, is a natural language that serves as the predominant sign language of Deaf communities. But, deaf people often have difficulties talking to abled people because not everyone knows all the alphabets of sign langauge. So, we need a mechanism to automate this.<br>
## Solution Strategy
__*Sign_Language*__ is a machine learning model which can detect the hand landmarks fron real-time video and show the alphabet associated with it. I had created a Hand landmark model using mediapipe. Further I had used the Random Forest Classifier from Intel oneAPI Optimised Scikit-Learn Library. This model can detect all the ASL alphabets ranging from A to Z (excluding J and Z).<br>
The dataset is made manually by running the __*collecting_data.py*__ that collects images from your webcam for all the above mentioned alphabets in the American Sign Language <br>
## Dependencies
opencv-python<br>
mediapipe<br>
scikit-learn intelex<br>
Numpy<br>
Pickle<br>
## To run Sign_Language
~~~~
$pip install scikit-learn intelex
$pip install opencv-python
$pip install mediapipe
$cd sign_Language
$python model_test.py
~~~~
