# Emotion Detection on Fer dataset using CNN & OpenCV
 Human emotion recognition plays a vital role in the interpersonal relationship. The automatic identification of emotions has been an active research topic since the early eras. Emotions are reflected from speech, hand, and gestures of the body and through facial expressions. As a human, I am sure; for most of you, it must be an easy task to judge a person by his emotion and communicate with them. But what if you want the machine to talk similarly by analyzing the feeling. Just as a human extracting and understanding the emotions, it is equally essential for the machine to understand the sentiment and then interact/respond to the human. So as part of this project, I try to resolve one of the issues and predict the emotion of a person using his facial features in real-time.

### Tasks: 
- Recognize each face based on the emotion shown in the facial expression into one of seven categories (0=**Angry**, 1=**Disgust**, 2=**Fear**, 3=**Happy**, 4=**Sad**, 5=**Surprise**, 6=**Neutral**)
- Prepare the dataset for the model
- Develop CNN model for recognizing facial expression of the images
- Fit the basic CNN model
- Save the model & load the saved weight to test the model
- Predict the facial expression of the uploaded image
- Use OpenCV and Haar Cascade File to check the emotion in real time

### Dataset: [Fer Dataset!!](https://www.kaggle.com/deadskull7/fer2013/download)
**fer2013** is an open-source dataset that consists of 35,887 grayscale, 48x48 sized face images with 7 different emotions, all labelled.
**Fer.csv** contains two columns, **emotion** and **pixels**. 

![Output 1](/images/fer.PNG)

- The **emotion** column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. 
- The **pixels** column contains a string surrounded in quotes for each image 
- **Classes:** 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral

### Output:

- I was able to acheive a **test accuracy of 67%**.

![Output 1](/images/anger.PNG)
