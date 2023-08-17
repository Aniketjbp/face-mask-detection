Mask Detection:-
WE are making a project to detect if a person is wearing mask or not.
Data:-
There is a folder "dataset" which contains two folders inside it.The dataset consisted of 1376 images, 690 face images "with masks" and 686 "without masks".
There is also a XML file named "haarcascade_frontalface_default.xml"
We use Convolutional neural network(CNN) for this.
Libraries we use are:-
1. Numpy
2. Matplotlib
3. os
4. openCv
5. Keras
6. sklearn
Output:-
The output comes from the webcam capturing the image and shows "MASK" or "NO MASK"
Overall High Accuracy:- 0.9868 (98.68%)

Usage:-
Step1:-Open suitable IDE with given libraries already installed
Step2:-Save "dataset" folder and XML file in the working directory of platform or here: 
dataset zip: https://drive.google.com/file/d/1Tr5WaaDzxAfd1Ya5uGPsjGa1JcIVH3Dq/view?usp=sharing
xml: https://drive.google.com/file/d/11es6yTokFFdJUsPefISsgyaYsMjY_23u/view?usp=sharing
Step3:-Compile and run the code, a webcam opens which takes your face image and give result as "MASK" and "NO MASK".