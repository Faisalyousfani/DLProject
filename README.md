# DLProject
this is a semester project built with OpenCV 

Objective:
This project is intended to detect face and recognize and label name of known person on his face and unknown if it’s unknown person

Libraries we used:
Numpy
OpenCV
Pickle
OS
Image from PIL

Algorithms

LBPH for recognizing the face from frame.
The Local Binary Pattern Histogram(LBPH) algorithm is a simple solution on face recognition problem, which can recognize both front face and side face. However, the recognition rate of LBPH algorithm under the conditions of illumination diversification, expression variation and attitude deflection is decreased

Classifier

HAARCASCADE used as classifier
What is HAAR CASCADE?
A Haar Cascade is basically a classifier which is used to detect the object for which it has been trained for, from the source. The Haar Cascade is trained by superimposing the positive image over a set of negative images. The training is generally done on a server and on various stages. Better results are obtained by using high quality images and increasing the amount of stages for which the classifier is trained.
What Is Classifier?
A classifier is a Supervised function (machine learning tool) where the learned (target) attribute is categorical ("nominal"). It is used after the learning process to classify new records (data) by giving them the best target attribute (prediction)




Step1 Capture Video
Step2 Detect Face.
step3 Draw Lines on Detected Face.
step3 train images..
step4 Detect Face.
Step5 Match with Dataset.
step6 compare confidence.
step7 search for id of that face.
step8 write name on the face detected.
 




