# FaceRecognition using one shot learning

The aim of this project was to get familiar with how to apply pretrained networks to provide solutions to our problems.

I aimed to use 'One shot Learning' where a model can perform face recognition with moderate accuracy by having only one picture of the person it is expected to recognize.

This idea largely borrows from the inceptionNet model where the feature vector of one of the final layers is used to represent a face and it's abstract features. 
Any deteced face in live video streaming is passed through this portion of the InceptionNet to get its feature vector. This is compared with the feature vector of all the existing database, and within a minimum distance, the closest value is used to recognize the face.
