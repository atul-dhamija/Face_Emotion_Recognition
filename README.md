# Face and Emotion Recognition Webapp

This project was aimed to deploy a *deep learning* application to recognise person's face and emotion.


## Dependencies

You can install Python dependencies using ``` pip install -r requirements.txt ``` , and it should just work. if you want to install package manually, here's a list:

 - Python 
 - Scikit Learn
 - Tensorflow
 - OpenCv
 - Pillow
 - Numpy
 - Matplotlib
 - dlib


## Dataset

The dataset consist of images of 15 celebrities, 100 for each for face recognition and consists of images of 7 types of emotions, 1300 for each emotion for emotion detection.

![repo5](https://user-images.githubusercontent.com/64823050/129590634-a0332790-0fc8-4dfd-a9ce-cf5a15010c10.jpg)

[Facial dataset](https://drive.google.com/file/d/197XCxvL1y8lHnGH8iVpffxl51ulN6Ql-/view)

[Emotion dataset](https://www.kaggle.com/debanga/facial-expression-recognition-challenge)

## Approach


### Step 1. Data Preprocessing
![repo6](https://user-images.githubusercontent.com/64823050/129591559-2dd90672-c5f7-4b17-b31d-384ade458f91.jpg)


### Step 2. Face and Emotion Recognition Model
![Pipeline for model](https://user-images.githubusercontent.com/64823050/127895363-ac056917-de12-4a7d-8098-fe39f23943aa.png)


### Step 3. WebApp Framework
![repo7](https://user-images.githubusercontent.com/64823050/129591794-b4fe2d45-27bf-4167-9be8-147a05c29cf7.jpg)

## Deployed Web Application

![repo8](https://user-images.githubusercontent.com/64823050/129592380-a2bb15ef-7301-4fc2-bf33-d46f39b8e4ae.jpg)

### [WebApp Link](https://face-emotion-analysis.herokuapp.com/)


## Result

![repo2](https://user-images.githubusercontent.com/64823050/127895916-5254f409-3e56-4541-9308-fd07874e7d7c.jpg)


## References

[Viola Jones Documentation](https://towardsdatascience.com/understanding-face-detection-with-the-viola-jones-object-detection-framework-c55cc2a9da14)

[Sklearn](https://scikit-learn.org/stable/user_guide.html)

[Viola Jones Research Paper](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-IJCV-01.pdf)

[Cascade Classifier](https://github.com/opencv/opencv/tree/master/data/haarcascades)

[Voting Classifier](https://towardsdatascience.com/how-voting-classifiers-work-f1c8e41d30ff)
