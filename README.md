# HaarCascade-based-object-Detection
We have used open cv based haarcascade for object detection(face and eyes). This was developed by Viola Paul and Michael Jones. 
Let's understand what is under the hood when we talk about HaarCascades-
Viola Jones developed this framework. This is one of the fastest frameworks amongst its counterparts(like CNN based framework).
Haar Cascades do not use image intensities directly. Haar Cascades basically contain four components -
1. Haar features
2. Integral Image
3. AdaBoost Classifier
4. Cascade Classifier.
Haar Features perceive an image as light and dark region. We subtract the sum of intensities in the dark region with the sum of intensities in the light region. 
Integral Image is basically intermediate representation of the image
AdaBoost Classifier uses a set of weak classifiers to build a hypothesis model called the strong classifier.
Cascade Classifier uses AdaBoost Classifier, moving from one stage to the other stage the number of weak classifier increases, if the output of the strong classifier is negative then the input is discarded.
Object Detection is a computer technology used widely nowadays and Haar Cascade Framework is the most efficient technique for object detection.



You can watch this video to get better insights. https://www.youtube.com/watch?v=88HdqNDQsEk
You can also read this amazing blog to get better grip over the concepts -https://towardsdatascience.com/computer-vision-detecting-objects-using-haar-cascade-classifier-4585472829a9
