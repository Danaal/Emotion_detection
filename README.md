# Emotion_detection

- The aim of this project is to classify emotions in real time.
- The data used for training is from kaggle competition fer2013 https://www.kaggle.com/deadskull7/fer2013. There are six emotions associated with the data which are [Angry, disgust,fear,happy,neutral,sad,surprise]
- I used a pretrained resnet18 model from pytorch and finetuned it.
- For the detection in real images (outside the dataset) and videos (real time), I use MTCNN for detecting the face to crop them out of the img and then I use the resnet for classification.
