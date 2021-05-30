# Python code of Analytics Vidhya - Age Detection of Actors

![image](https://user-images.githubusercontent.com/73815389/120074580-22c9cd00-c0bb-11eb-8ebc-8a28fd8d1de6.png)


Facial feature analysis has always been a topic of interest mainly due to its applicability. Deep Learning techniques are now making it possible for face analysis to be not just a dream but a reality. This practice problem is get us more acquainted with deep learning. 

Analytics Vidhya solution link : [Click here](https://www.analyticsvidhya.com/blog/2017/06/hands-on-with-deep-learning-solution-for-age-detection-practice-problem/?utm_source=practice-problem-age-detection&utm_medium=Datahack)


### Dataset used: IMFDB

Indian Movie Face database (IMFDB) is a large unconstrained face database consisting of 34512 images of 100 Indian actors collected from more than 100 videos. All the images are manually selected and cropped from the video frames resulting in a high degree of variability interms of scale, pose, expression, illumination, age, resolution, occlusion, and makeup. IMFDB is the first face database that provides a detailed annotation of every image in terms of age, pose, gender, expression and type of occlusion that may help other face related applications. 

### Task:

The task is to predict the age of a person from his or her facial attributes. The problem has been converted to a multiclass problem with classes as Young, Middle and Old.


In the program, I have used 5 models

1. Model 1: Accuracy-74%
2. Model 2: Accuracy-76%
3. Model 3: Accuracy-77%
4. Model 4: Accuracy-75%
5. Model 5-Tensorflow GPU : Accuracy-80% (on test data in Analytics Vidhya scored-79.79%) HIGHEST
